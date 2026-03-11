# E-Commerce Product Recommendation System

## Project Description
This project implements an E-Commerce Product Recommendation System that suggests products to users based on their behavior and interests. The system combines multiple recommendation approaches including collaborative filtering, content-based filtering, hybrid recommendation, and popularity-based recommendation. The frontend is developed using React and the backend is implemented using Flask.

---

## Software Versions

| Software | Version |
|--------|--------|
| Python | 3.9 or 3.10 |
| Node.js | 16 or above |
| npm | 8 or above |
| Git | Latest |

---

## Libraries Used

| Library | Version |
|------|------|
| flask | 2.3.2 |
| flask-cors | 4.0.0 |
| pandas | 1.5.3 |
| numpy | 1.23.5 |
| scikit-learn | 1.2.2 |
| requests | 2.31.0 |

---

## Technologies Used

Frontend  
React  
Vite  
Tailwind CSS  

Backend  
Python  
Flask  

Machine Learning  
Pandas  
NumPy  
Scikit-learn  

---

## Project Structure

```
E-Commerce-Product-Recommendation
│
├── backend
│   ├── models
│   ├── hybrid_recommender.py
│   ├── popularity_model.py
│   ├── new_user.py
│   └── app.py
│
├── frontend
│   ├── components
│   ├── pages
│   └── App.js
│
└── README.md
```


---

## Installation Requirements

The following software must be installed before running the project:

Python  
Node.js  
npm  
Git  

---

## Steps to Execute the Project in Another System

### Step 1: Clone the Repository


git clone https://github.com/Yagna29/E-Commerce-Product-Recommendation-.git


### Step 2: Navigate to Project Folder


cd E-Commerce-Product-Recommendation-


---

## Backend Setup

### Step 3: Navigate to Backend Folder


cd backend


### Step 4: Install Required Python Libraries


pip install flask
pip install flask-cors
pip install pandas
pip install numpy
pip install scikit-learn
pip install requests


or


pip install -r requirements.txt


### Step 5: Run Backend Server


python app.py


Backend will run at:


http://127.0.0.1:5000


---

## Frontend Setup

Open a new terminal.

### Step 6: Navigate to Frontend Folder


cd frontend


### Step 7: Install Dependencies


npm install


### Step 8: Start React Application


npm start


Frontend will run at:


http://localhost:3000


---

## How the System Works

1. The user opens the web application.
2. The React frontend sends requests to the Flask backend.
3. The backend processes recommendation algorithms.
4. Recommended products are returned to the frontend.
5. The frontend displays the recommendations to the user.

---

## Recommendation Methods

Collaborative Filtering  
Content-Based Filtering  
Hybrid Recommendation  
Popularity-Based Recommendation  

---

## Contributors

| Name | Contribution |
|-----|--------------|
| Suryaja | Content-Based Recommendation, Hybrid Model, Explainable AI |
| Yamini | Collaborative Filtering, UI Development, Backend |
| Yagna Priya | Popularity-Based Recommendation, Pixel API Integration, Backend |
| Gayatri Kowsalya | Data Preprocessing |

---
