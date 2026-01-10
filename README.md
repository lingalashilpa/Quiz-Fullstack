🧠##**Quiz Full-Stack Application**

📌 **Project Overview**

This is a Full-Stack Quiz Application developed using Angular (Frontend) and FastAPI (Backend).
The application allows users to take a quiz, submit their scores, and view a leaderboard.

The frontend handles the user interface and quiz interaction, while the backend manages quiz data, score submission, and leaderboard APIs.

🧩 **Project Type**

✅ Full-Stack Web Application

Frontend: Angular

Backend: FastAPI (Python)

🎯 **What We Did in This Project**

Frontend:

Created a responsive quiz UI using Angular

Displayed quiz questions dynamically

Collected user answers

Calculated user score

Sent score data to backend using HTTP requests

Displayed leaderboard data

Backend:

Built REST APIs using FastAPI

Returned quiz questions to frontend

Accepted username and score submissions

Sorted scores to create a leaderboard

Enabled CORS to allow frontend-backend communication

Prepared MongoDB connection for future database storage

🛠️ #**Technologies Used**

🔹 **Frontend Technologies**

Angular

TypeScript

HTML

CSS

Bootstrap (optional)

🔹 **Backend Technologies**

Python

FastAPI

Pydantic

MongoDB

PyMongo

Uvicorn

CORS Middleware

📂 **Project Structure**

quiz-fullstack/
│
├── frontend/                # Angular frontend
│   ├── src/
│   ├── angular.json
│   └── package.json
│
├── backend/                 # FastAPI backend
│   ├── main.py
│   ├── db.py
│   └── requirements.txt
│
└── README.md

🔹 Frontend Details (Angular)

Runs on: http://localhost:4200

Fetches quiz questions from backend

Sends user score to backend

Displays leaderboard

Run Frontend
cd frontend
npm install
ng serve

🔹 Backend Details (FastAPI)

Runs on: http://127.0.0.1:8000

Provides quiz and leaderboard APIs

API Endpoints
Method	Endpoint	Description
GET	/	Home route
GET	/quiz	Get quiz questions
POST	/submit_score	Submit username & score
GET	/leaderboard	Get leaderboard

🚀 **How to Run the Project (Step-by-Step)**

✅ **Backend Setup**

Install Python (3.8+)

python --version


Install dependencies

pip install fastapi uvicorn pymongo


Start MongoDB
Make sure MongoDB is running on:

mongodb://localhost:27017/


Run the backend server

uvicorn main:app --reload


Backend available at:

http://127.0.0.1:8000


Swagger API Docs:

http://127.0.0.1:8000/docs

✅ **Frontend Setup**

Go to frontend folder

cd frontend


Install packages

npm install


Run Angular app

ng serve


Frontend available at:

http://localhost:4200

🔗 **Frontend–Backend Connection**

Quiz API:

http://127.0.0.1:8000/quiz


Submit score API:

http://127.0.0.1:8000/submit_score


Leaderboard API:

http://127.0.0.1:8000/leaderboard


✨ **Features**

Responsive quiz interface

Real-time leaderboard

REST API architecture

Clear separation of frontend & backend

Easy to extend and scale

👩‍💻 **Author**

Shilpa
Full-Stack Quiz Application 🚀
