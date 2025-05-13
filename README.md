# 🎬 Cinema Booking System

This project is a backend prototype for a cinema ticket booking system. It was developed to practice backend development skills, including REST API design, database integration, and user authentication.

---

## 🛠️ Technologies Used

- **Python 3.10+**
- **FastAPI** – for building RESTful APIs
- **SQLAlchemy** – ORM for database interactions
- **PostgreSQL** – relational database
- **Alembic** – for database migrations
- **Pydantic** – for data validation
- **Uvicorn** – ASGI server for FastAPI

---

## 📦 Features

- User registration and authentication
- Movie listings with details
- Showtimes and seat availability
- Booking tickets with seat selection
- Admin panel for managing movies and schedules

---

## 🚀 Getting Started

### Prerequisites

- Python 3.10 or higher
- PostgreSQL database

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/turdalievargen32/Cinema.git
   cd Cinema
   ```

2. **Create and activate a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Configure the database:**

   - Create a PostgreSQL database.
   - Update the `DATABASE_URL` in the `.env` file with your database credentials.

5. **Apply migrations:**

   ```bash
   alembic upgrade head
   ```

6. **Run the application:**

   ```bash
   uvicorn main:app --reload
   ```

   The API will be available at `http://127.0.0.1:8000`.

---

## 📄 API Documentation

Once the application is running, you can access the interactive API docs at:

- Swagger UI: `http://127.0.0.1:8000/docs`
- ReDoc: `http://127.0.0.1:8000/redoc`

---

## 📌 Project Status

This project is a work in progress and serves as a learning platform for backend development with FastAPI and PostgreSQL. Contributions and suggestions are welcome!

---
## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
