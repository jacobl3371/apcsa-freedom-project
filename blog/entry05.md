# Entry 5

### Putting Together The MVP
Not that I had the separate CRUD todo-list app done as well, I was ready to combine the code from both tutorials into a fullstack application with auth. In order for all of the operations done by the user to only be accessible if they are logged in and authenticated into the website, I had to make sure to wrap the routes to create, read, update and delete the app content in the same `ProtectedRoutes` function that the DashboardPage component was already wrapped in. 

![image-1](https://github.com/jacobl3371/apcsa-freedom-project/tree/main/blog)

This would redirect the user back to the login page if they were not authenticated, or the verify-email page if they did already sign up better never verified their account.

![image-2](https://github.com/jacobl3371/apcsa-freedom-project/blob/main/tool/image-18.png)

![image-3](https://github.com/jacobl3371/apcsa-freedom-project/blob/main/tool/image-19.png)

This part was simple but it was really tedious to have to go back and actually delete the functions for the CRUD functionalities in each respective React component and replace it with the direct call of that function after it is imported from the `useAuthStore()` function in authStore.js 

![image-4](https://github.com/jacobl3371/apcsa-freedom-project/blob/main/tool/image-21.png)

![image-5](https://github.com/jacobl3371/apcsa-freedom-project/blob/main/tool/image-22.png)

Otherwise the app would break as it couldn't check that the user is authenticated before accessing these routes, which use axios in of themselves to fetch data from the backend.

![image-6](https://github.com/jacobl3371/apcsa-freedom-project/blob/main/tool/image-20.png)

### Engineering Design Process
I am in the 5th and final stage of the engineering design process for creating my application, I have an MVP which is up and running, combining the authentication features which consist of routes and controllers that manipulate the `User` object and additional CRUD features that require their own routes and controllers to make changes to instances of the `Note` object, having a fully working note-taking/todolist app where you can sign up and login and save your notes, and implementing advanced authentication features as well that require the user to verify their email before they can use their use their account which allows them to then utilize the option to reset their password if they were to forget it.

I asked Shi Jun to deploy my app for me on his own personal server. vercel doesn't support the deployment of the backend authentication, but for convenience I asked Shi Jun to deploy the entire app for me on the dedicated server: https://todolister.kyson.dev/

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
