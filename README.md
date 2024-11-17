# 📚 MERN-BookStore: A Full-Stack Web Application for Managing Books

## Overview

MERN-BookStore is a comprehensive web application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js) that allows users to efficiently manage and operate a books collection. This project incorporates essential CRUD (Create, Read, Update, Delete) operations to handle books, authors, and other relevant data within the bookstore's inventory.

## How to run this project:

### For Frontend 
Follow the below steps to run the project: 
- Firstly clone or unzip the project folder.
* Go to the frontend directory by using the following command ``` cd frontend ```.
* * create a **.env.local** file in the backend root directory as the same level where the **package.json** is located and keep the following environment variables there:
```
>>> Stepup firebase app and configure the environment

VITE_API_KEY="AIzaSyCXvDIC4MPrkaMdeg_O2iij88wLpfj3qBA"
VITE_Auth_Domain="book-store-mern-app.firebaseapp.com"
VITE_PROJECT_ID="book-store-mern-app"
VITE_STORAGE_BUCKET="book-store-mern-app.appspot.com"
VITE_MESSAGING_SENDERID= "205632822247"
VITE_APPID="1:205632822247:web:b0db0ec66bf6de0bbb3b42"
```
+ Then run `` npm install `` commend to install node dependencies.
- Finally, to run the project, use ``npm run dev`` command.


### For Backend
Follow the below steps to run the project: 
- Firstly clone or unzip the project folder.
* Go to the backend directory by using the following command ``` cd backend```.
+ Then run `` npm install `` commend to install node dependencies.
* create a **.env** file in the backend root directory as the same level where the **package.json** is located and keep the following environment variables there: 
```
DB_URL = "mongodb+srv://helpyourassistant:pqam0Mwv3Vwv8Off@cluster0.qc3bq.mongodb.net/book-store?retryWrites=true&w=majority&appName=Cluster0"

JWT_SECRET_KEY = 'bc992a20cb6706f741433686be814e3df45e57ea1c2fc85f9dbb0ef7df12308a669bfa7c976368ff32e32f6541480ce9ec1b122242f9b1257ab669026aeaf16'

Note: Please setup mongodb and change the MongoDB url and set your jwt secret key above.
```

- Finally, to run the project, use ``npm run start:dev`` command.

## Key Features

1. 🔐 **User Authentication:**
   - Secure user registration and login system for both customers and bookstore staff.
   - Differentiate between admin and regular user roles to control access and privileges.

2. 📖 **Book Management:**
   - Create, read, update, and delete books in the app.
   - Associate books with authors, genres, and categories.

3. 👨‍💼 **Author Management:**
   - Link authors to their respective books for easy navigation.

4. 📚 **Genre Management:**
   - Add, edit, and delete genres and categories as needed.

5. 🌟 **User-Friendly Interface:**
   - Utilize React.js to create a responsive and user-friendly front-end.
   - Intuitive and visually appealing design for a smooth user experience.

6. 🔒 **Security and Validation:**
    - Implement authentication and authorization mechanisms to secure data.
    - Validate user inputs to prevent malicious actions.

7. 🚀 **Scalability and Performance:**
    - Optimize database queries and server routes for improved performance.
    - Prepare the application for potential scaling by using best practices.

## Technologies Used

- 🌐 **Front-end:** React.js, HTML, CSS(Tailwind), JavaScript
- ⚙️ **Back-end:** Node.js, Express.js
- 🗃️ **Database:** MongoDB (Atlas Cloud Service)
- 🔑 **Authentication:** JSON Web Tokens (JWT), Firebase,
- 🔄 **Version Control:** Git
- ☁️ **Deployment:** AWS

## Project Structure

`1)` `Server`: 
- `Connection`: Manages the database connection.
- `Controllers`: Handles request handling and business logic.
- `Models`: Defines data models/schema for the database.
- `Middlewares`: Implements middleware functions for request handling.
- `Routes`: Defines API routes for the application.
- `utils`: Houses utility functions and helper modules.

`2)` `Client`:
- `Assets`: Stores static assets like images and styles.
- `Components`: Contains reusable React components.
- `Pages`: Defines the main application pages.

## Contributing

Contributions to the MERN-BookStore are welcome! Please follow these steps:

1. 🍴 Fork the repository.
2. 🌿 Create a new branch for your feature or fix.
3. 🛠️ Make your changes and commit them.
4. 🚀 Push your changes to your fork.
5. 🔄 Create a pull request to the main repository.

Contributions and feedback are welcome! If you find any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue. Please follow the contribution guidelines.

👨‍💻 **Author**: Krishnendu Das (@krishDas2023TM93599)