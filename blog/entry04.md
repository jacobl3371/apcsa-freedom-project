# Entry 4

### Final Challenges Faced In Building The Frontend
![image-1](https://github.com/jacobl3371/apcsa-freedom-project/blob/main/tool/image-16.png)

Above is the correct working code to get the notes title and content for the `updateNotes` functionality.

At first the page to update the notes wasn't working and every time the user would try to click to it, it would break the entire application and there would just be a black screen at the URL for that note-ID, until the user navigates back to the homepage.

![image-2](https://github.com/jacobl3371/apcsa-freedom-project/blob/main/tool/image-15.png)

This was happening because I was trying to import the notes title and content as `title` and `content` variables themselves which I thought I could just access from `useParams()` as I did not understand the functionality of the useParams hook in React, which is intended to fetch string data from the site URL. Instead I had to make sure to use `note.title` and `note.content` to access the title and content properties of the `note` object defined by the Mongoose Schema used to represent MongoDB objects in my application.

### EDP
I currently am still in the 4th stage of the Engineering Design Process for my project. I have completed the entire CRUD functionality, with both the backend and frontend, and am ready to move on to taking code I already have for the authentication and combining it with these todolist app CRUD features to form my MVP.

### Skills
1. A skill that I strengthened was logical reasoning, as I had to understand that the title and content variables could not be accessed from the URL parameters, which is what the `useParams()` function does. I had to understand that the title and content were variables associated with the `note` object and which could be called with the `.` operator.
2. A second skill that I strengthened by working through this part of my project was Learning On Your Own, as I had to figure out what useParams() does, which I had never utilized before following this tutorial which I have currently finished, as well as when to use the `.` operator.

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
