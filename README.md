# Bus_Ticketing_System

This bus ticketing system provides a platform for managing bus schedules, fare calculations, and user accounts. The system includes user registration and login, a central dashboard for easy navigation, and features for adding, viewing, and updating schedules. Administrators can generate detailed reports, calculate fares based on routes, and manage a comprehensive list of registered users, streamlining operations for smoother travel management.

## Table of Contents

- [Project Interfaces](#project-interfaces)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Set Up Environment Variables](#set-up-environment-variables)
- [Run the Project](#run-the-project)

## Project Interfaces

### SignUp page
![Screenshot 1](Frontend/screenshots/screenshot1.png)

### Login page
![Screenshot 2](Frontend/screenshots/screenshot2.png)

### Dashboard
![Screenshot 3](Frontend/screenshots/screenshot3.JPG)

### Add Schedule
![Screenshot 4](Frontend/screenshots/screenshot4.JPG)

### View Schedule
![Screenshot 5](Frontend/screenshots/screenshot5.JPG)

### Update Schedule
![Screenshot 6](Frontend/screenshots/screenshot6.JPG)

### Generate Report
![Screenshot 7](Frontend/screenshots/screenshot7.JPG)

### Fare Calculation
![Screenshot 8](Frontend/screenshots/screenshot8.JPG)

### View Users
![Screenshot 9](Frontend/screenshots/screenshot9.JPG)

## Technologies Used

- React.js
- Node.js
- Express.js
- MongoDB

## Prerequisites

Before you begin, ensure you have met the following requirements:

1. **Node.js**: [Download Node.js](https://nodejs.org/en/download/)
   - Node.js is required to run the backend and frontend of the application.

2. **npm**: Comes bundled with Node.js.

3. **MongoDB**: 
   - You can either install MongoDB locally or use MongoDB Atlas.
   - **Local Installation**: [Install MongoDB Community Edition](https://docs.mongodb.com/manual/installation/)
   - **MongoDB Atlas Setup**: [Getting Started with Atlas](https://docs.atlas.mongodb.com/getting-started/)

4. **Postman** (optional): Useful for testing API endpoints.
   - **Postman**: [Download Postman](https://www.postman.com/downloads/)

5. **Git**: [Download Git](https://git-scm.com/downloads)

## Installation

1. **Clone the repository:**

      ```bash
      git clone https://github.com/PamudiNaveesha/Bus_Ticketing_System.git
      cd Bus_Ticketing_System

2. **Install dependencies:**

   1. **For the backend**

      ```bash
      cd BACKEND
      npm install

   2. **For the frontend**

      ```bash
      cd frontend
      npm install

## Set Up Environment Variables

1. Open the `.env` file in the **BACKEND** folder of your project.
2. Add the following line to the file:
   
   ```plaintext
   MONGODB_URI=mongodb+srv://<username>:<password>@<clustername>.mongodb.net/<database>
   
4. **MONGODB_URI**: This is the key that your application will use to access the MongoDB database.
5. **MongoDB URI Format**: Replace `<username>`, `<password>`, `<clustername>`, and `<database>` with your actual MongoDB credentials and database name.
  
## Run the Project

   1. **For the backend**

      ```bash
      cd BACKEND
      npm run dev

   2. **For the frontend**

      ```bash
      cd frontend
      npm start 
