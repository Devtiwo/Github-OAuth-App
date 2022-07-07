# Github OAuth App

This project is to showcase the implementation of a github OAuth authentication feature.

# Getting Started

- Reister or login to a github account and have nodejs installed on your computer

- Register a new OAuth app in your github account by going to settings - developer settings - OAuth apps - Register a new application button

- Fill in the form with the information below\

  Application Name: OAuth Project (or any name for your project)\
  Homepage URL: http://localhost:3000 \
  Authorization Callback URL: http://localhost:3000/auth/github/callback

- Generate a new Client secret, copy it and the client Id and save somewhere safe.

- clone this repository with the command below\
    `git clone https://github.com/Devtiwo/Github-OAuth-App.git` (https) OR\
    `git clone git@github.com:Devtiwo/Github-OAuth-App.git` (ssh)

- Navigate to the directory with\
    `cd Github-OAuth-App`

- Install dependencies by typing\
    `npm install`

- Insert your clientID and client secret in the .env file

- Then start the server by typing\
    `node app.js`

- Navigate to `localhost:3000` in your web browser to view the front end 



# To Test

1. Login to the app using your github accout
2. You should be redirected to the authorization page from github.
3. After authorizing with github, You should be logged in and be able to view your account information in the account tab
4. Log out
