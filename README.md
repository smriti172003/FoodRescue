# FoodRescue

A web application which is useful for management of food donation and collection activities.  
![image](https://github.com/user-attachments/assets/4d7644ec-4f19-49ed-b347-e819e1f49dd7)



## Table of Contents  

- [Features](#features)
- [Technologies used](#technologies-used)
- [npm packages used](#npm-packages-used)
- [Prerequisites](#prerequisites)
- [Installation and setup](#installation-and-setup)
- [Useful Links](#useful-links)
- [Contact](#contact)

## Features

- The system consists of three types of users: admins, donors and agents.
- Admins: They control all the activities and accept/reject donations and select agents.
- Donors: They are the driving users of the application who donate food.
- Agents: They are responsible for collecting food from homes of food donors.
- Each user should have an account.
- Every user also have a dashboard where they can view several things in short summary.
- The application provides signup, login and logout functionalities.

DFD Diagrams:
LEVEL-0
![image](https://github.com/user-attachments/assets/3f4ced5a-8334-4333-98fd-5c790512a8a7)

LEVEL-1
![image](https://github.com/user-attachments/assets/dfa96d80-1f03-487e-9655-265cfef34fd2)

### Donor Features
- Donors make the donation request for food with basic details.
- Donors' donation requests can be accepted or rejected and the status can be easily tracked by them.
- Donors can view their current incomplete donations (if any).
- Donors can also view all their past donations.
- Donors can update their profile.
  
As a Donor
![image](https://github.com/user-attachments/assets/b04d085e-3b7e-43ca-85ea-5f0f3a0b236c)
![image](https://github.com/user-attachments/assets/03b8ade1-6f92-4b08-ab66-886b1aa8a04a)
![image](https://github.com/user-attachments/assets/8336cef6-24ec-406c-8170-e6ba1531b9b2)
![image](https://github.com/user-attachments/assets/7e72d56c-7d0d-4990-bef9-d27c87e7767f)
![image](https://github.com/user-attachments/assets/4746fc02-4c91-43ea-aeb7-bfda97835d01)


### Admin Features

- Admins receive all the requests made by donors.
- Admins can accept or reject the donation requests depending upon the details provided by a donor.
- If accepted, admins can assign an agent to a donation for collecting donation from the donor's home.
- Admins can view all the pending donations along with status.
- Admins can view all the donations that they have received.
- Admins can also view all the agents in the application.
- Admins can update their profile.

  As a Admin
  ![image](https://github.com/user-attachments/assets/184409d3-f05b-437c-bc50-405320b776b7)
  ![image](https://github.com/user-attachments/assets/7ade3ca2-6ba2-414e-b9c7-72a3e3ed0486)
  ![image](https://github.com/user-attachments/assets/c465f7a5-ce18-4cf6-9b92-317888cc4c26)
  ![image](https://github.com/user-attachments/assets/f9f6b0a4-1b4b-4ef5-9fb3-90f276fe540e)


### Agent Features

- Agents will receive notifications from admins to collect food from donor's homes.
- Agents can mark their collection upon collection of food from donor's home.
- Agents can also view all those food donations which have been collected by them previously.
- Agents can update their profile.

  As a agent
  ![image](https://github.com/user-attachments/assets/b750e911-998b-4286-addc-1f27e92a994e)
  ![image](https://github.com/user-attachments/assets/27e5ad5c-6e37-4adf-9c56-901146773bc0)
  ![image](https://github.com/user-attachments/assets/1c9cf873-0f8f-4b34-a9b4-3965b5480585)
  ![image](https://github.com/user-attachments/assets/dad4048c-a340-492b-bace-96daaf7a32fa)


## Technologies used

- HTML
- CSS
- Bootstrap
- Javascript
- Node.js
- Express.js
- Mongodb
- ejs

## npm packages used

- express
- ejs
- express-ejs-layouts
- mongoose
- express-session
- bcryptjs
- passport
- passport-local
- connect-flash
- method-override
- dotenv

## Prerequisites

For running the application:

- Node.js must be installed on the system.
- You should have a MongoDB database.
- You should have a code editor (preferred: VS Code)

## Installation and Setup

1. Install all the dependencies
   ```sh
   npm install
   ```
2. Create a file named ".env" and enter the following credentials:
   ```js
   MONGO_URI = yourmongouri;
   ```
3. Run the web application
   ```sh
   npm start
   ```
4. Open http://localhost:5000
5. You need to first signup and then login to run the application.

## Useful Links

- Demo: https://food-aid-aayush.herokuapp.com/
- Nodejs download: https://nodejs.org/
- VS Code download: https://code.visualstudio.com/
- Tutorials: https://www.w3schools.com/
- npmjs docs: https://docs.npmjs.com/
- Expressjs docs: https://expressjs.com/
- Bootstrap docs: https://getbootstrap.com/docs/5.1/getting-started/introduction/
- Mongoosejs docs: https://mongoosejs.com/docs/index.html
- Mongodb atlas: https://www.mongodb.com/cloud/atlas/register
- Mongodb docs: https://docs.mongodb.com/manual/introduction/
- Nodemailer docs: https://nodemailer.com/
- Github docs: https://docs.github.com/en/get-started/quickstart/hello-world
- Git cheatsheet: https://education.github.com/git-cheat-sheet-education.pdf
- VS Code keyboard shortcuts: https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf


