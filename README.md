# FastAPI User Manager

A clean, lightweight CRUD REST API built with FastAPI, SQLite, SQLAlchemy, and Pydantic.

## Overview
This project demonstrates modern backend development practices with Python:
- FastAPI: High-performance ASGI framework with async support.
- SQLAlchemy: ORM for defining and interacting with database models.
- Pydantic: Data validation and serialization using Python type hints.
- Uvicorn: ASGI server for running the app.

## Features
- Create a new user (POST /users/)
- Retrieve all users (GET /users/)
- Retrieve a user by ID (GET /users/{id})
- Delete a user (DELETE /users/{id})
- Interactive API documentation available at /docs

## Getting Started

```bash
git clone https://github.com/kiranbabu-pedda/fastapi-user-manager.git
cd fastapi-user-manager
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
```

## API Documentation
Visit http://127.0.0.1:8000/docs to explore and test endpoints using Swagger UI.

## Next Steps (Suggestions for Improvement)
- Add update functionality (PUT /users/{id})
- Implement JWT-based authentication
- Dockerize the application for deployment
- Use PostgreSQL or MySQL for production environments
- Add automated testing using pytest

## License
This project is open-source and available under the MIT License.

Feel free to fork this repository and enhance it further.
