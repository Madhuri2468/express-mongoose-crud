Setup a Full CRUD REST API with Express and Mongoose
📌 Project Overview

This project demonstrates how to develop a full CRUD REST API (Create, Read, Update, Delete) using Express and Mongoose to manage student records in a MongoDB database.

🚀 Getting Started
1. Setup Project

Create a Node.js project and install dependencies:

mkdir express-mongoose-crud
cd express-mongoose-crud
npm init -y
npm install express mongoose body-parser

2. Create Schema & Model

Connect to MongoDB (schoolDB) using Mongoose.

Define a Student schema with fields:

name (String, required)

rollNo (Number, required, unique)

branch (String)

year (Number)

email (String)

Create a Student model from the schema.

3. Build CRUD Routes

Implement API routes:

POST /students → Create a student record

GET /students → Read all students

GET /students/:id → Read a single student by ID

PUT /students/:id → Update a student by ID

DELETE /students/:id → Delete a student by ID

4. Run the Project

Start the server:

node app.js


Open your browser or API client at http://localhost:3000.

📂 Project Structure
express-mongoose-crud/
 ├── app.js
 ├── package.json
 └── README.md

✅ Output
![WhatsApp Image 2025-09-19 at 10 27 44_30d190ab](https://github.com/user-attachments/assets/7739bc55-4b12-452f-a7e4-5e01e7f75154)


![WhatsApp Image 2025-09-19 at 10 28 24_69705f49](https://github.com/user-attachments/assets/afc16aa9-4fd7-4bd5-8845-e81b83d65366)
