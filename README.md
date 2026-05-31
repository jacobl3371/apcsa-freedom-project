# APCSA Freedom Project
by **Jacob Levit**

## Context
I am a student at [HSTAT](https://www.hstat.org/) in the [Software Engineering Program](https://hstatsep.github.io/). The "Freedom Project" for AP Computer Science A is a year-long project all about making anything using technology.

For my project, I chose to independently study the **MERN** stack (MongoDB, Express, React and Node.js) in order to help me make a **note taking web app with advanced authentication features**.

## Links

[Product](https://todolister.kyson.dev) --> Mailtrap only allows sending emails on demo domain (to account-owner email), you can test my app by signing in with these test account credentials: 

email: mailtrap7@onionmail.org

password: Password1$


[Presentation](https://docs.google.com/presentation/d/1tA1Vdf2fFsZ9deEGQy46DowYgaVXTAflZ9NuF_R40-Q/edit?pli=1&slide=id.g3e51b4ef0da_2_0#slide=id.g3e51b4ef0da_2_0)

## Implications
##### PROS
* The user can sign in from anywhere as the application is not just restricted to one device and works on any browser.
* Keeps privacy and security in mind --> signing and logging in are not restricted over Tor and VPNs like many applications tend to do
* Advanced auth features --> requires the user to verify that their email exists by using a verification code before they can create their account
  * There is also an option to reset your password if you forgot it, which can be an extremely helpful feature.
 
##### CONS
* Currently if you want to reset your password, clicking the button to do so in the email only sends the user to the the url of the page you are on for that current email service, plus the "reset-password/*reset-token*" url. So if you wanted to change your password you would have to just copy the "reset-password/*reset-token*" part and paste it after the app url for the todolist app
* No file upload option for images or voice memoirs
* You can only use the demo email sending domain --> mailtrap isn't that good anyways, I tried configuring my own domain to allow sending for all users but didn't manage to figure out how. Either way, I aim to learn how to implement my own email sending server for account verification


## Blog
Below you will find my blog about how I made my project.

* [Entry 1](blog/entry01.md)
* [Entry 2](blog/entry02.md)
* [Entry 3](blog/entry03.md)
* [Entry 4](blog/entry04.md)
* [Entry 5](blog/entry05.md)
* [Entry 6](blog/entry06.md)
* [Entry 7](blog/entry07.md)
* [Entry 8](blog/entry08.md)
* [Entry 9](blog/entry09.md)
* [Entry 10](blog/entry10.md)
