# Alumni Tracker
![alumni-track](https://socialify.git.ci/Chandra-Kishor201123/alumni-tracking/image?language=1&owner=1&name=1&stargazers=1&theme=Light)

Alumni Tracker is a  web application developed using the MERN (MongoDB, Express.js, React, Node.js) stack. It serves  a platform for alumni to connect, share updates, and engage with the admin seamlessly. The application is divided into user and admin interfaces, each equipped with distinct features and functionalities.


## Deployment
This website is hosted on Vercel. You can access the deployed application using the following link:

[Alumni Tracker](https://alumni-tracking-chandra.vercel.app)

 
## Features

### User Interface:

- **Authentication and Welcome Email:**
  - Users can sign up securely with JWT authentication.
  - After signing up, a friendly welcome email is automatically sent to the user's email address.
  - This project uses a Nodemailer to handle sending emails.

- **Post Creation:**
  - Users can create posts with textual content and upload images.
  - Image storage is facilitated through Cloudinary.

- **Engagement:**
  - Users can like, comment, and view posts.
  - delete posts and comments.
  - post images can be uploaded using camera or file system.
  - Users can see the profile page of other users.
  
- **FAQ Section:**
  - A dedicated FAQ section enables users to ask questions from the admin, providing an interactive space for inquiries.

- **Password Management:**
  - Password reset functionality allows users to regain their password  access via email verification.

- **Enhanced User Search:**
  - Users can search for other users using various credentials.
  - Search options include email, roll number, year, and branch.
  - Users can also view all the users belonging to a particular branch and to a particular year.

### Admin Interface:

- **Enhanced Email Verification:**
  - Admin accounts require additional verification through email confirmation with the Head of Department (HOD).

- **Mobile OTP-Based Password Reset:**
  - Admins can reset passwords securely using mobile OTPs.
  - Used Twilio Sms Api to send OTP for reset passwords.

- **User Management:**
  - Admins have the ability to search for users and delete profiles when necessary.

- **Communication Hub:**
  - Mass email functionality allows admins to send updates to all users or individual emails.
  - Notices can be sent directly to users, viewable and downloadable from their dashboards.

- **FAQ Administration:**
  - Admins can manage and respond to user queries in the FAQ section.

## Screenshots
![screenshots1](https://github.com/aashish649/alumni-track/assets/150827208/49817231-c2b1-4efa-a8d1-c9ef4ffd9059)

![Screenshots2](https://github.com/aashish649/alumni-track/assets/150827208/862728c2-364b-4dec-aa65-4f06fcb00b31)

![Screenshot (155)](https://github.com/aashish649/alumni-track/assets/150827208/2ee68f14-b2cd-4013-b4fa-dac736e4f585)

![Screenshot (156)](https://github.com/aashish649/alumni-track/assets/150827208/7654eb57-7d02-4127-89d4-5c8ffaf0e956)

![Screenshot (157)](https://github.com/aashish649/alumni-track/assets/150827208/87815397-c2ae-496f-8d5d-f632aa94d82d)

![Screenshot (159)](https://github.com/aashish649/alumni-track/assets/150827208/ab360cb4-e77e-4f8e-bc8d-ac1392fafd45)

## Technologies Used

### Frontend

| Logo | Technology |
| --- | --- |
| <img src="https://www.svgrepo.com/show/493719/react-javascript-js-framework-facebook.svg" alt="React Logo" width="30"/> | React |
|  <img src="https://www.svgrepo.com/show/372883/javascript.svg" alt="React Logo" width="30"/> | Javascript |
| <img src="https://www.svgrepo.com/show/374118/tailwind.svg" alt="CSS Logo" width="30"/> | Tailwind css |

### Backend

| Logo | Technology |
| --- | --- |
| <img src="https://www.vectorlogo.zone/logos/nodejs/nodejs-icon.svg" alt="Node.js Logo" width="30"/> | Node.js |
| <img src="https://www.vectorlogo.zone/logos/expressjs/expressjs-icon.svg" alt="Express.js Logo" width="30"/> | Express.js |

### Database

| Logo | Technology |
| --- | --- |
| <img src="https://www.vectorlogo.zone/logos/mongodb/mongodb-icon.svg" alt="MongoDB Logo" width="30"/> | MongoDB |


### Image Storage

| Logo | Technology |
| --- | --- |
| <img src="https://www.svgrepo.com/show/353566/cloudinary.svg" alt="Cloudinary Logo" width="30"/> | Cloudinary |


### Version Control

| Logo | Technology |
| --- | --- |
| <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git Logo" width="30"/> | Git |
| <img src="https://www.vectorlogo.zone/logos/github/github-icon.svg" alt="GitHub Logo" width="30"/> | GitHub |


### Authentication

- JWT (JSON Web Tokens) - [Learn More](https://jwt.io/)
- Email Verification with Nodemailer - [Nodemailer](https://nodemailer.com/)
- Mobile OTP with Twilio SMS API - [Twilio](https://www.twilio.com/en-us)


## Setup Instructions
1. **Clone the Repository:**
   ```bash
   git clone repo_url
   cd alumni-tracker
2.Install Dependencies:
  -Navigate to the client directory and install client-side dependencies.
  
    cd client && npm install
    
-Navigate to the server directory and install server-side dependencies.

    cd server && npm install

3.Environment Variables:
  - Create a `.env` file in the server directory.
  - Add necessary environment variables to the `.env` file (MongoDB URl, Cloudinary credentials, Twilio credentials, etc.).

4.Run the Application: 
  -In the client directory: `npm start`
  -In the server directory: `npm start`
