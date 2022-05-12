# GitHub-OAuth App
> The purpose of this project is to demonstrate authenticating an application via GitHub. 



## General Information
- This project is part of the "User Authentication & Authorization" section in the Codecademy curriculum
- The task was to implement an OAuth login using the express-session, passport modules



## Technologies Used
- Node.js 14.17.6
- ejs 3.1.6
- express 4.17.1
- express-partials 0.3.0
- express-session 1.17.2
- passport 0.4.1



## Features
- Authenticating an application via GitHub using an OAuth login
- Display information from the connected GitHub account



## Screenshots
![Example screenshot](https://i.ibb.co/HdZrJ2b/oauth.png)



## Setup
The dependencies which are necessary to run this app can be found in the package.json file.

1. Register an OAuth application in GitHub to retrieve a clientID and client secret
2. Clone the repo
3. Navigate to the project folder in the terminal and install the necessary NPM dependencies
```
npm install
```
4. Use the clientID and client secret as values for the respective variables in app.js
5. Run the app typing
```
node app.js
```
in your terminal and visit localhost:3000/login in your browser.



## Learnings
- Registering an OAuth application in GitHub
- Setting up express-session
- Configuring passport
- Using Passport Session Serializers
- Implementing OAuth Routes



## Project Status
The project is finished.



## Acknowledgements
- This project is part of the Codecademy Full-Stack-Engineer Curriculum. The focus was implementing the logic for the OAuth login. The front-end was implemented beforehand.



