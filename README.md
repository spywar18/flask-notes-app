# Flask Notes App

A simple Flask web application for user authentication and note-taking.

## Features

- User registration and login (with hashed passwords)
- Add and delete personal notes
- Flash messages for feedback
- SQLite database with SQLAlchemy ORM
- Bootstrap 4 UI

## Technologies

- Python 3
- Flask
- Flask-Login
- Flask-SQLAlchemy
- JavaScript (for note deletion)
- Bootstrap 4

## Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/spywar18/flask-notes-app.git
   cd flask-notes-app
   ```

2. **Create a virtual environment and activate it:**
   ```sh
   python -m venv venv
   venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

4. **Run the app:**
   ```sh
   python main.py
   ```

5. **Open in browser:**  
   Visit [http://127.0.0.1:5000](http://127.0.0.1:5000)

## Folder Structure

```
flask web app/
│
├── main.py
├── website/
│   ├── __init__.py
│   ├── auth.py
│   ├── models.py
│   ├── views.py
│   ├── static/
│   │   └── index.js
│   └── templates/
│       ├── base.html
│       ├── home.html
│       ├── login.html
│       └── sign_up.html
```

## License

MIT License