# Entry 2

### Challeges Encountered When Building Authentication
Once I had finished the auth features I was facing trouble deploying my MERN stack app to Vercel, since Vercel is only built to work with its native NextJS auth. The site itself will still run but the auth features like signing up and logging in won't work on Vercel.

![image-1](https://github.com/jacobl3371/apcsa-freedom-project/blob/main/tool/image.png)

This message in the console is basically saying that there is an error connecting to the endpoints I have created within the backend of my application, which are fetched to the frontend using Axios within the authStore.js file.

![image-2](https://github.com/jacobl3371/apcsa-freedom-project/blob/main/tool/image-2.png)

These endpoints were all working when tested on the local server, so this was was clearly an issue with the deployment on Vercel.

Once I deployed the app with Render instead I was able to get it working and login into the account I had created. (I can't signup with a new email unless I clear my database in my cluster on MongoDB Atlas since the service I used for email verification and account recovery, Mailtrap, is only free for a limited number of messages to the demo email account that I signed up with.)

The dashboard page once you enter after successfully logging in on the working render deployment looks like so:

![image-3](https://github.com/jacobl3371/apcsa-freedom-project/blob/main/tool/image-5.png)


### Engineering Design Process
I have building finished the entire account-creation and login system that will be implemented in my app. I had it up running on Render but that deployment no longer works so I have considered using a personal server once I finish the app. Next I'm going to start building and then implementing the actual CRUD features that the user can perform once they are signed up and logged into the application.


[Previous](entry01.md) | [Next](entry03.md)

[Home](../README.md)
