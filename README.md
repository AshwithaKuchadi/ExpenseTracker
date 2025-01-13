# Expense Tracker (Fullstack)

An Expense Tracker application built using a full-stack architecture. This application allows users to track their expenses, categorize them, and visualize spending habits with an intuitive UI.

---

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Requirements](#requirements)
- [Setup Instructions](#setup-instructions)
- [How to Run](#how-to-run)
- [API Endpoints](#api-endpoints)
- [Usage](#usage)
- [Demo](#demo)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- Add, edit, and delete expense entries.
- Categorize expenses by type (e.g., Food, Travel, Utilities).
- Track expenses over a specific time range.
- View spending habits via charts/graphs.
- Full-stack implementation with a RESTful API.

---

## Technologies Used

### Frontend
- React
- Bootstrap/Tailwind CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB

---

## Requirements

Ensure the following tools are installed on your system:

- Node.js (v14+)
- npm or yarn
- MongoDB (local or cloud instance)
- Git

---

## Setup Instructions

### Clone the Repository

```bash
git clone https://github.com/Maclinz/expense-tracker_fullstack.git
Navigate to the Project Directory
bash
Copy code
cd expense-tracker_fullstack

Backend Setup
Navigate to the server directory:
bash
Copy code
cd server
Install dependencies:

bash
Copy code
npm install
Configure the environment variables:

Create a .env file in the server directory.

Add the following variables:

env
Copy code
PORT=5000
MONGO_URI=mongodb://localhost:27017/expense_tracker
JWT_SECRET=your_secret_key
Start the backend server:

bash
Copy code
npm start
By default, the server runs on http://localhost:5000.

Frontend Setup
Navigate to the client directory:

bash
Copy code
cd ../client
Install dependencies:

bash
Copy code
npm install
Start the React development server:

bash
Copy code
npm start
The frontend will run on http://localhost:3000.

## How to Run
Ensure MongoDB is running on your system.

Start MongoDB locally or use a MongoDB cloud instance.
Start the backend server (in the server directory):

bash
Copy code
npm start
Start the frontend server (in the client directory):

bash
Copy code
npm start
Open your browser and navigate to http://localhost:3000.

## API Endpoints
Here are the key API endpoints used in the backend:

Authentication
POST /api/auth/register - Register a new user.
POST /api/auth/login - Login and receive a JWT token.
Expenses
GET /api/expenses - Get all expenses for the logged-in user.
POST /api/expenses - Add a new expense.
PUT /api/expenses/:id - Update an expense.
DELETE /api/expenses/:id - Delete an expense.

Usage
Add Expenses:
Add expenses by category, amount, and date.

Visualize Spending:
View graphs and charts to analyze your expenses.

Manage Expenses:
Edit or delete expense entries as needed.

## Demo
demo link of the project
https://drive.google.com/file/d/1rebRIDTf50ZUHdj-z-Aoq-oaq4oQ9LPK/view?usp=drive_link

# Contributing
Contributions are welcome! Follow these steps:

## Fork the repository.
Create a new branch for your feature or bug fix:
bash
Copy code
git checkout -b feature-name
Commit your changes:
bash
Copy code
git commit -m "Add new feature"
Push to your branch:
bash
Copy code
git push origin feature-name
Open a pull request on GitHub.

#License
This project is licensed under the MIT License. See the LICENSE file for details.
