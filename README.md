
# EMS - Event Management System

This is a web-portal to register meetings and track member behaviour.
The interface allows users to host a meeting as well as check-in/out from a meeting. The backend is written using Node.js/Express.js and uses MongoDB for storage.
The key features are: 
* Email and SMS sent to host when visitor checks-in
* Email sent to visitor when visitor checks-out<br/>
<b>Note:</b> `Nexmo SMS API` is used to send SMS. Free subscription has been used, that allows SMS to be sent between `9:00am` and `9:00pm` only.

## Preview
### Web Portal
![GIF Preview](https://github.com/akshaj1999/EMS/blob/master/Screenshots/vlc-record-2019-11-28-21h00m47s.gif)

### SMS and Email
<img src="https://github.com/akshaj1999/EMS/blob/master/Screenshots/IMG-20191128-WA0027.jpg" width="300" height="600"/> <img src="https://github.com/akshaj1999/EMS/blob/master/Screenshots/IMG-20191128-WA0026.jpg" width="300" height="600"/>

## Technologies Used
### Front-End
* HTML
* CSS
* JS/jQuery
* Bootstrap

### Back-End
* Node.js/Express.js
* MongoDB (Hosted on [mongodb atlas](https://www.mongodb.com/cloud/atlas)) 

## Run Locally
### System Prerequistites
* node
* npm

### Using the code
* Clone this repo: `git clone https://github.com/akshaj1999/EMS.git`
* Run `npm install` to install dependencies
* `cd` into the repository root and start server: `node server.js`
* In the browser, navigate to url: `localhost:8080` to use the portal.
