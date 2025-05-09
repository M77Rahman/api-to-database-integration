# API to Database Integration

This project is a **Flask-based web application** designed to integrate with an **SQLite** database for performing **CRUD** (Create, Read, Update, Delete) operations. The app features basic input validation for data integrity and includes detailed testing using **Postman**.

## Technologies Used
- **Flask**: A lightweight web framework for Python.
- **SQLite**: A simple, serverless SQL database used to store the records.
- **Python 3**: The programming language used to build the application.
- **Postman**: A tool for testing APIs (used to test the endpoints).

## Features
- **API Endpoints**:
  - `POST /api/records`: Create a new record in the database.
  - `GET /api/records`: Retrieve all records from the database.
  - **Input Validation**: Ensures that required fields are filled out correctly before being added to the database.

## Getting Started

### Prerequisites
To run this project locally, you need Python 3 and the following libraries:
- Flask
- SQLite3

You can install the required dependencies by using `pip` and a `requirements.txt` file. If you don't have one, you can manually install Flask and SQLite3 by running:
```bash
pip install flask sqlite3
