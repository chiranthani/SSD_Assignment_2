# Google Calendar - Creating Event using OAuth

#Getting started 

Install 

Clone or download the application from the repository and run npm install to install all the relevant dependencies.

Google Developer console 
Navigate to google developer console to create an application for the demo. Use the client id and client secret of created application in the below section to run the demo.

Google API Credentials 
Add following information to the server.js file variables 

Client_Id  = “your application client Id”
Client_Secret = “ Your client secret”
Redirection_Url = “http://localhost:4000/api/event/oauthcallback”


Run 
Run the application using following commands

nodemon server 
or 
npm run serve 
