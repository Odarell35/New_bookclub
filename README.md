# eBookClub

**eBookClub** is a Flask-based web application designed for book enthusiasts to connect, share, and discuss their favorite reads. The app features user authentication, a database-driven architecture, and modular views to ensure a seamless user experience.

---

## Features

- **User Authentication**: Secure login system using Flask-Login.
- **Database Integration**: Persistent storage with SQLite for user and book data.
- **Blueprints**: Organized routing and modular architecture for maintainability.
- **Error Handling**: Custom error responses for improved debugging and user feedback.

---

## Getting Started

### Prerequisites

Ensure you have the following installed:

- [Python 3.8+](https://www.python.org/)
- [Pipenv](https://pipenv.pypa.io/en/latest/)
- Git

---

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Odarell35/eBookClub.git
   cd eBookClub
   ```
2. **Set up the virtual environment**:

   ```bash
   pipenv install
   pipenv shell
   ```

3. **Install dependencies**:
   ```bash
    pip install -r requirements.txt
   ```
4. **Set up the database**:

```bash
python -c "from web_site import db; db.create_all()"
```

---

## Additional Details

### Technologies Used

- **Backend Framework**: Flask
- **Database**: SQLite (SQLAlchemy for ORM)
- **Frontend**: HTML, CSS, and JavaScript (static files directory)
- **Authentication**: Flask-Login for secure user sessions
- **Environment Management**: Pipenv

---
