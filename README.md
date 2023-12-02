# To-Do-App with Django and React.js

This is a simple To-Do application built with Django on the backend and React.js on the frontend. It allows users to create, manage, and delete their tasks.

## Features

- **Create Tasks**: Users can add new tasks with titles and descriptions.
- **Update Tasks**: Ability to edit existing tasks.
- **Delete Tasks**: Users can remove tasks they no longer need.
- **Mark as Completed**: Option to mark tasks as completed.

## Prerequisites

Before running the application, ensure you have the following installed:

- Python
- Django
- npm (Node Package Manager)

## Installation

### Backend (Django)

1. Clone the repository.
2. Navigate to the `backend` directory.
3. Create a virtual environment: `python -m venv env`.
4. Activate the virtual environment:
    - On Windows: `.\env\Scripts\activate`
    - On macOS and Linux: `source env/bin/activate`
5. Install the required Python packages: `pip install -r requirements.txt`.
6. Apply migrations: `python manage.py migrate`.
7. Start the Django server: `python manage.py runserver`.

### Frontend (React.js)

1. Navigate to the `frontend` directory.
2. Install dependencies: `npm install`.
3. Start the React development server: `npm start`.

## Usage

- Access the application at `http://localhost:3000` in your web browser.
- Sign up or log in to start managing your to-do list.
- Create, update, and delete tasks as needed.

## Tech Stack

### Backend

- Django
- Django REST Framework
- SQLite (or your preferred database)

### Frontend

- React.js
- Axios (for API requests)
- Bootstrap (or any preferred CSS framework)

