# Tool Learning Log

## Tool: MERN Stack

## Project: Music Playing Web App

---

### 10/5/25:
I have been learning the MERN stack recently in order to help me develop interactive real-time web applications that store user data. (MongoDB, Express, React, Nodejs)

dev.to is a resource for developers and on there I found a blog post with a link to a playlist for a (complete MERN stack tutorial)[https://www.youtube.com/playlist?list=PL63c_Ws9ecIQkH5xD6JW4cf2VporjzSRW] to build a simple to-do-list app. I followed the playlist up until part 16 where he started building the React frontend using Material UI--a library that ships pre-built and designed React components--which I realized wouldn't help me in my actual fundamental learning of React and the combined tools in my tech stack for two reasons:
    a. What reason do I have to use Material UI in any future projects anyway?...
    b. Using Material UI when I'm learning the basics hinders my learning of making components from scratch, which I will definitely need to know how to do anyways whether for this project or later on.

So I moved on from that tutorial to a (more relevant and up-to-date)[https://www.youtube.com/watch?v=pmvEgZC55Cg] MERN stack course using Vite and Tailwind CSS for the frontend, and which also showcased the integration of some advanced features such as email verification and password-reset/account-recovery.

I had finished that tutorial over the summer and have a [website up](https://foss-todolister.onrender.com/login) and running that I had to deploy with render, since a MERN stack app with authentication can't be properly deployed on Vercel despite trying numerous times as Vercel is only built to work with its native NextJS auth. The site itself will still run but the auth features like signing up and logging in won't work on Vercel.

![alt text](image.png)

That red error message is thanks to this snippet of React and TailwindCSS code:

![alt text](image-1.png)

And the message in the console is basically saying that there is an error connecting to the endpoints I have created within the backend of my application, which are fetched to the frontend using Axios within the authStore.js file.

![alt text](image-2.png)

If the login endpoint call worked but the password was wrong then it would show an error saying that the credentials are invalid.

![alt text](image-3.png)

I also integrated the account recovery and email verifification features using mailtrap, but its only free for a limited number of messages to the demo email account that I signed up with.

The dashboard page once you enter after successfully logging in on the working render deployment looks like so:

![alt text](image-5.png)

Right now I only have an account-creation and login system created, and I am planning to integrate the CRUD (create, read, update, delete) features for the actual todo list portion of my MERN-practice app, before I move on to building a music app and scrap most of the todo list app code.

I will have all of my code for the todo-lister tinker-mini-project in [this repo](https://github.com/jacobl3371/todolister), and then I will make another repository for my main freedom project music app that I will be working on until the end of the year.
