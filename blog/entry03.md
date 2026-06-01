# Entry 3

### Beginning to Implement New CRUD Features
I finished the authentication features of the app and moved on to [another MERN stack tutorial](https://www.youtube.com/watch?v=Ea9rrRj9e0Y) from the same channel to help me better understand how to implement the Create Read Update Delete (CRUD) functionalities in my application.

I ran into some issues like `dotenv` not being configured properly, as I was missing `dotenv.config()` in my server.js file

![image-1](https://github.com/jacobl3371/apcsa-freedom-project/blob/main/tool/image-6.png)

And other common mistakes like forgetting the `async` keyword before asynchronous operations that use await:

![image-2](https://github.com/jacobl3371/apcsa-freedom-project/blob/main/tool/image-9.png)

I also ran into a problem when I began to build the frontend as I was using the [wrong url](https://v3.tailwindcss.com/docs/installation) to configure Tailwind CSS in my application. This was causing the class styling not to be outputted:

![image-1](https://github.com/jacobl3371/apcsa-freedom-project/blob/main/tool/image-10.png)

![image-2](https://github.com/jacobl3371/apcsa-freedom-project/blob/main/tool/image-11.png)

I had to use the [Vite-specific installation](https://v3.tailwindcss.com/docs/guides/vite) for configuring my application with React.js and Vite, which then made the class-styling show up on the web-page.

![image-3](https://github.com/jacobl3371/apcsa-freedom-project/blob/main/tool/image-14.png)

### EDP
I am currently still in the 3rd and 4th stage of the Engineering Design Process, I have completed my entire backend for additional application features which require CRUD functionalities, and am completing the frontend and working towards my MVP.

### Skills
1. One skill that I strengthened was once again attention to detail, as I had missed the line of code to configure dotenv in my application (`dotenv.config()`), making it so that I couldn't inject environment variables into my application from the `.env` file.
2. Another skill that I strengthened was communication, as I needed to reach out to Shi Jun to find out that I was using the wrong link to configure TailwindCSS in my React Vite application. This also ties into keeping up with and using the appropriate modern documentation for the different libraries and frameworks that you're working with.

[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)
