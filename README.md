ReachInBox Assignment
The assignment is to develop a server-based application using Node.js and Express that will parse and analyze emails from both Google and Outlook accounts. The application will use AI to automatically generate and send responses based on the email's content. Key technologies include the OpenAI API for AI-driven responses, the Google APIs for accessing Google email services, Axios for making HTTP requests, and BullMQ for task scheduling and queue processing.
![image](https://github.com/user-attachments/assets/b49a9adf-767c-4980-87c8-04e8a5a36789)

Technologies used:Node.js
Express.js
OpenAI
Google APIs
npm packages used:
dotenv
Axios
bullMQ
google-auth-library
ioredis

Setup
Clone the repository to your local machine:
git clone https://github.com/Krishnasharma382/Reachinbox/tree/main
Navigate to the root directory of the project directory :
cd server
Run npm install to install all the dependencies
Create a .env file in the root directory with the same IDs as specified in the documentation.
Running the server
To start the server, run the following command in your terminal
npm start
This will start the server at localhost:5000 (or whatever port you have specified). or we can use backend deployed link also.

To start the worker.js file, run the following command in your terminal
npm run server

