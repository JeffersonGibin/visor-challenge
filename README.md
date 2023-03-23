# Visor Challenge

This project is part of *Visor's  recruiting process*. Below you can find a description of the challenge, the architecture I used and all the warehouses involved.

### Challenge:

 Develop a chat app should be able to send messages through an input area, then draw those same messages in a chat as well as the automatic answers from the algorithm.


### What it needs to do:
- write messages;
- send messages;
- receive answer
- messages every time a message is sent.

**Note:** The complexity of the development is up to the developer's capabilities and knowledge. The way the challenge is tackled will determine the participant's level and role.

**There are a few restrictions:**
- only use JavaScript & Javascript frameworks;
- must have back-end and front-end logic;
- if a database is created for this purpose, it should be a non-relation database. Besides this, feel free to make the best of your skills in this exercise but take into consideration.


**Some tips:**
- write clean code;
- create a well organised project;
- use good code practices;
- make sure the logic is explained in the best way possible.



## Architecture

Below you will find an image detailing a little
about the architecture of the project.


This architecture came from the idea of applying the Twelve Factory App.

If you don't know what is [visit here](https://12factor.net/)

I can tell you that applying all techniques was impossible because time was short. But you can see that we have
an authentication service, service to create accounts, service to work with socket and a front-end
who is responsible for consuming all of this.

![image](https://user-images.githubusercontent.com/6215779/226993622-4663a5d3-a7e8-484c-8686-73666855e4cf.png)


## Platform

### Sign-in

![image](https://user-images.githubusercontent.com/6215779/227002963-db455c08-83ce-44e5-b79b-894646d7031c.png)

### Sign-up

![image](https://user-images.githubusercontent.com/6215779/227003233-5bbb9f42-12f6-4e35-897c-4cd887e1b596.png)


To register you only need your name, email and a password. The password must be 6 characters long and must consist of numbers and lowercase letters.


### Chat

![image](https://user-images.githubusercontent.com/6215779/227083970-e274e11c-7a8f-4c2e-87b0-0d43130c7a94.png)


## Repositories

 #### Front-end:
- [Web-app](https://github.com/JeffersonGibin/visor-chat-webapp): Front-end of project.
 #### Back-end:
- [Account Lambda](https://github.com/JeffersonGibin/visor-account-lmb-api): service to create a count.
- [Auth Lambda](https://github.com/JeffersonGibin/visor-auth-lmb-api): service to authenticate users.
- [Socket Chat Lambda](https://github.com/JeffersonGibin/visor-chat-lmb-socket): service to chat with AI.
