# Openverse Media Search App

This is a full-stack web application that allows users to register, log in, and search for openly licensed media using the [Openverse API](https://openverse.org/). The app is built with:

- **Frontend**: React + Vite + TailwindCSS
- **Backend**: Flask (Python) + SQLite
- **Auth**: JSON Web Tokens (JWT)
- **Dev Tools**: Docker & Docker Compose

---

## 🚀 Features

- User registration & login
- Token-based authentication
- Search for images via Openverse
- View personal search history
- Responsive UI with TailwindCSS
- Fully Dockerized

---

## 🐳 Getting Started with Docker

### 1. Clone the Repository

```bash
git clone https://github.com/rsharma2116/software-engineering.git
cd software-engineering/openverse_app
```

### 2. Build and Start the App

```bash
docker compose up --build
```

- Frontend: [http://localhost:5173](http://localhost:5173)
- Backend API: [http://localhost:5000/api](http://localhost:5000/api)

---

## 🧪 Manual Dev Setup (Without Docker)

### Backend (Flask)

```bash
cd backend
python -m venv venv
venv\Scripts\activate        # Use `source venv/bin/activate` on Mac/Linux
pip install -r requirements.txt
python run.py
```

### Frontend (React)

```bash
cd frontend
npm install
npm run dev
```

---

## 📁 Project Structure

```
openverse_app/
├── backend/
│   ├── app/
│   ├── requirements.txt
│   ├── run.py
│   └── Dockerfile
├── frontend/
│   ├── src/
│   ├── package.json
│   └── Dockerfile
└── docker-compose.yml
```

---

## 📄 License

This project is for educational use only. Images are fetched from [Openverse](https://openverse.org/), which aggregates from various sources under Creative Commons licenses.
