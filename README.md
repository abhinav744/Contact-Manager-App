📞 Contact Manager App (Node.js + Express + MongoDB)

This is a Node.js-based Contact Manager App that allows users to add, edit, delete, and manage contacts efficiently using a backend API.



🚀 Features

📋 RESTful API for managing contacts

🛠 CRUD operations (Create, Read, Update, Delete)

💾 MongoDB database integration

🔐 User authentication (if implemented)

📱 Responsive API design for frontend integration

🛠 Tech Stack

Backend: Node.js, Express.js

Database: MongoDB (Mongoose ORM)

API Testing: Postman, Swagger (if applicable)

Authentication (Optional): JWT, bcrypt

Frontend (Optional): React.js (if integrated)

📁 Project Structure


/Contact-Manager-App-Using-Node.js

│── /src

│   │── /routes         # API route handlers

│   │── /controllers    # Business logic for contacts

│   │── /models         # Mongoose schemas

│   │── /middleware     # Middleware (auth, validation)

│   │── server.js       # Main server file

│── /config             # Database and environment configs

│── package.json        # Dependencies and scripts

│── .env                # Environment variables

│── README.md           # Documentation

🚀 Installation & Setup

Clone the repository





git clone https://github.com/abhinav744/Contact-Manager-App-Using-Node.js.git

cd Contact-Manager-App-Using-Node.js

Install dependencies




npm install

Set up environment variables


Create a .env file in the root directory and add:




PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

Start the development server





npm start

The API should now be running at http://localhost:5000/.



🔧 API Endpoints

Method	Endpoint	Description

GET	/api/contacts	Get all contacts

POST	/api/contacts	Add a new contact

GET	/api/contacts/:id	Get a single contact

PUT	/api/contacts/:id	Update a contact

DELETE	/api/contacts/:id	Delete a contact

📌 Contributing

Contributions are welcome! Feel free to:

✅ Fork the repository

✅ Create a new branch

✅ Make changes and submit a pull request

