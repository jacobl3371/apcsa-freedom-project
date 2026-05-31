# Presentation Plan

## Hook
* "What if you could build your own notes app?..."

## Product
* Transition from hook --> video demo of application, logging in, seeing the notes already in the database, CRUD functionalities, logout

## Process
<u>Backend</u>:
* Object Modeling Schema for Node.js and MongoDB --> Mongoose.js
   * Create the `Notes` and `User` object
* Controllers are used to perform functionalities on instances of objects on the database --> controller functions imported and called on routes which allows for the routing of all of the CRUD operations within my app.
  * These routes are then imported into my server.js file and called with `express.use()`

* Briefly touch on advanced auth features

<u>Frontend</u>
* Requires axios, authSore.js file with `useAuthStore()` function (`create` object imported from Zustand)
  * Functions in `useAuthStore` are imported into React component files and called directly
    * These functions need to be in the `useAuthStore()` function so that when the routes are wrapped with the `ProtectedRoute` function, it will redirect the user back to the login or signup page if they are not authenticated.
   
* Talk about frontend challenges

## Conclusion
* useParams() can only be used to access text variables from the URL of the current webpage, and can not be used to access or update the state of variables related to objects within your code
* Keeping a plan in mind --> I had bigger aspirations and originally wanted to make a music app
* Talk about the necessity of collaboration --> I couldn't have ever solved all of the challenges I faced along the way otherwise
