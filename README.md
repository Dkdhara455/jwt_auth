FastAPI JWT Authentication with Database
This is a clean, modular FastAPI project implementing user authentication using JWT tokens with password hashing, registration, login, protected routes, and user deletion. The app uses SQLite via SQLAlchemy as the database.
Features
-User registration with strong password validation
-Secure password hashing with bcrypt
-JWT token generation and verification
-Login endpoint returns JWT token
-Protected endpoint requiring valid JWT token
-Delete logged-in user endpoint
-Modular, clean code structure

jwt_auth/
├── app/
│   ├── __init__.py
│   ├── main.py
│   ├── models.py
│   ├── schemas.py
│   ├── auth.py
│   ├── dependencies.py
│   ├── crud.py
│   ├── database.py
│   └── config.py
├── requirements.txt
├── README.md

## for insallaisation
pip install -r requirements.txt

## run the surver
uvicorn app.main:app --reload
