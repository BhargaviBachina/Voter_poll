# Voter Poll Application

## Introduction

The Voter Poll Application is a web-based platform designed to facilitate the voting process for general elections in India. It allows voters to register, cast their votes, and view election results. The application ensures secure, efficient, and user-friendly interactions, leveraging modern web technologies.

## Key Features

- **Voter Registration:** Secure registration using unique voter IDs.
- **Voting Process:** Allows registered voters to cast their votes securely.
- **Real-time Results:** Displays election results with vote counts for each party.
- **Administrative Controls:** Tools for managing the voting process and marking it as complete.
- **Security:** Ensures data integrity and prevents multiple votes from a single voter.

## Installation Guide

### Prerequisites

- **Python 3.7+**
- **Node.js 12+ and npm**
- **Django 3.2+**
- **Django REST Framework**
- **React**

### Backend Installation (Django)

1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-repo/voter-poll-app.git
   cd voter-poll-app
2.  **Set Up Virtual Environment**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
3. **Install Dependencies**
    ```sh
   pip install django djangorestframework
4. **Migrate the Database**
   ```sh
   python manage.py makemigrations
   python manage.py migrate
5. **Create Admin User and Run Server**
   ```sh
   python manage.py createsuperuser
   python manage.py runserver

### Frontend Installation (React)

1. **Create a React App**
   ```sh
   npx create-react-app voter-poll-app
   cd voter-poll-app

2. **Install Required Packages**
   ```sh
   npm install axios react-router-dom

3. **Run the React app**
   ```sh
   npm start


