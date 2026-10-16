# Python Bank Management System

A Python-based Bank Management System with a web interface built using Streamlit. This project allows users to create and manage bank accounts and perform basic banking operations.

## Features

* Create a new bank account
* Deposit money
* Withdraw money
* View account details
* Update account information
* Delete an account
* Generate a unique account number
* Store account information using JSON
* Interactive web interface built with Streamlit

## Technologies Used

* Python
* Object-Oriented Programming (OOP)
* Streamlit
* JSON
* Random and String modules

## Project Structure

Python-Bank-Management-System/
├── app.py
├── hello.py
├── main.py
├── requirements.txt
└── data.json

* app.py — Streamlit web interface.
* hello.py — Contains the main banking logic and account management functions.
* main.py — Command-line version of the project.
* requirements.txt — Lists the required Python libraries.
* data.json — Stores account information locally and is created or updated by the application.

## Installation and Setup

### 1. Clone the repository

git clone YOUR_REPOSITORY_URL

Replace YOUR_REPOSITORY_URL with your GitHub repository URL.

### 2. Open the project folder


cd Python-Bank-Management-System


### 3. Install dependencies


python -m pip install -r requirements.txt


### 4. Run the application

python -m streamlit run app.py


The application will open in your browser. If it does not open automatically, visit the local address shown in the terminal.

## Learning Outcomes

This project helped me practise Python classes and methods, JSON file handling, data management, and building a web application using Streamlit.

## Note

This is a learning project and is not intended for real banking transactions. The current implementation stores PINs in plain text. Do not use real account details or deploy it for public use without implementing appropriate security measures.


