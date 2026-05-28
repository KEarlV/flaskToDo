---

 🆕 REST API Feature 

This fork adds a full JSON REST API for managing todos programmatically.

### New API Endpoints

| Method | Route | Description |
|--------|-------|-------------|
| POST | /api/todos | Create a new todo |
| GET | /api/todos | Get all todos |
| GET | /api/todos/<id> | Get a single todo |
| PUT | /api/todos/<id> | Update a todo |
| DELETE | /api/todos/<id> | Delete a todo |

### API Documentation (Swagger)
Run the app and go to: http://localhost:5000/apidocs

### Running Tests
pip install pytest pytest-cov
pytest tests/ -v --cov=todos_api --cov-report=term-missing

### New Dependencies
pip install flasgger pytest pytest-cov
