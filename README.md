# FastAPI-LinkShortner
A fast and lightweight URL Shortener API built with FastAPI, Pydantic, and SQLAlchemy featuring custom link generation and live click analytics.
# FastAPI URL Shortener with Analytics

A lightweight, high-performance **URL Shortener API** built with **FastAPI**, **Pydantic v2**, and **SQLAlchemy (SQLite)**. This project automatically generates short, unique keys for long URLs, redirects users seamlessly, and tracks total click analytics.

## 🚀 Features
- **URL Validation**: Ensures only valid HTTP/HTTPS URLs are accepted using Pydantic.
- **Dynamic Redirection**: Fast `307 Temporary Redirect` responses to destination URLs.
- **Click Tracking**: Automatically increments and stores analytics counters upon each redirect.
- **Auto-generated Docs**: Fully documented interactive API endpoints via Swagger UI.

## 🛠️ Tech Stack
- **Framework:** FastAPI
- **Data Validation:** Pydantic (v2)
- **Database ORM:** SQLAlchemy
- **Database:** SQLite (File-based)
- **Server:** Uvicorn

## 📦 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd YOUR_REPO_NAME
   ```

2. **Create and activate a virtual environment:**
   ```bash
   # On macOS/Linux
   python3 -m venv venv
   source venv/bin/activate

   # On Windows
   python -m venv venv
   venv\Scripts\activate
   ```

3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## 🚦 Running the Application

Start the local development server using Uvicorn:
```bash
uvicorn main:app --reload
```
Once started, the API will be available at `http://127.0.0.1:8000`.

## 📖 API Documentation
FastAPI provides interactive API documentation out of the box. Open your browser and navigate to:
- **Swagger UI:** `http://127.0.0`
- **ReDoc:** `http://127.0.0`

## 👥 Author
- Created by **Shahbaz**
