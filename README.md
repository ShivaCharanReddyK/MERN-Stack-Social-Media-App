# MERN-Stack-Social-Media-App

In this project, we will build and deploy a fully responsive FullStack or MERN Stack Social Media application using MongoDB, ExpressJs, Reactjs, NodeJs


n the project directory, you can run:

npm start
Runs the app in the development mode.
Open http://localhost:3000 to view it in your browser.

The page will reload when you make changes.
You may also see any lint errors in the console.


SERVER OR BACKEND

Firstly move to the server directory eg: cd server



1. Create a .env file

  The .env file will contain the following:

  i. MONGODB_URL = database connection string

  ii. JWT_SECRET_KEY = your secreate key

  iii. PORT = 8800

  iv. AUTH_EMAIL= email address

  v. AUTH_PASSWORD= email access password

  vi. APP_URL = http://localhost:8800



  Note: I used hotmail account to send verification email, so you can just create one because hotmail account is reliable in product and has no configuration.



  Alos, chnage API_URL when you deploy your app else use localhost with the appropriate port number



2. Run npm install to install the packages

3. Run npm start to start the server
