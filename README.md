# Task Manager App

A Task Manager application built with Django, Django REST Framework, React.js, Bootstrap, HTML, and CSS. This app allows users to manage their daily tasks efficiently with features like task creation, editing, deleting, and marking tasks as complete.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Task Management**: Create, update, delete, and mark tasks as completed.
- **Responsive Design**: Fully responsive UI built with Bootstrap.
- **RESTful API**: Backend powered by Django REST Framework for seamless data handling.
- **Modern Frontend**: Frontend developed with React.js for a dynamic and interactive user experience.

## Tech Stack
- **Backend**: Django, Django REST Framework
- **Frontend**: React.js, HTML, CSS, Bootstrap
- **Database**: SQLite (default), easily switchable to PostgreSQL or MySQL
- **Others**: Axios for API requests, Redux (optional) for state management

## Installation

### Prerequisites
- Python 3.x
- Django, Restframework
- Node.js & npm
- Git

### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/task-manager.git
   cd task-manager
2. Set up a virtual environment:
bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

3. Install backend dependencies:
bash
pip install -r requirements.txt

4. Run migrations:
bash
python manage.py migrate

5.Start the Django development server:
bash
python manage.py runserver

6.Frontend Setup
Navigate to the frontend directory:
bash
cd frontend

7.Install frontend dependencies:
bash
npm install

8.Start the React development server:
bash
npm start

9.Usage
Open your browser and go to http://localhost:8000 for the backend and http://localhost:3000 for the frontend.
Use the task management features to add, update, or delete your tasks.
API Endpoints

10.The backend provides a RESTful API to interact with tasks. Below are some key endpoints:

GET /api/tasks/: Retrieve a list of tasks.
POST /api/tasks/: Create a new task.
PUT /api/tasks/<id>/: Update an existing task.
DELETE /api/tasks/<id>/: Delete a task.
For more details, refer to the API Documentation.

11.Contributing
Contributions are welcome! Follow these steps to contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a pull request.
