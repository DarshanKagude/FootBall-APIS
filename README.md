# FootBall-APIS
# ⚽ Upcoming Soccer Matches Web App

A simple full-stack web application that displays a list of **upcoming soccer matches** by fetching data from a public API. The backend is powered by **Flask**, and the frontend uses **HTML with Jinja2 templates**.

---

## 🌍 Live Data Source

**API Used:**  
[Free API Live Football Data - RapidAPI](https://rapidapi.com/Free-api-live/api/free-api-live-football-data/)  
- Base URL: `https://free-api-live-football-data.p.rapidapi.com`
- Endpoint used in this project:  
  `/football-popular-leagues`

> 📌 Note: This API requires a free [RapidAPI](https://rapidapi.com/) account and an API key.

---

## 🛠️ Technologies Used

### 🔙 Backend
- **Flask** – Lightweight Python web framework
- **Flask-CORS** – Handles cross-origin requests
- **Requests** – For calling the external football API

### 🔜 Frontend
- **HTML** – Rendered using Flask’s `render_template`
- **Jinja2** – Templating engine used in Flask

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/DarshanKagude/FootBall-APIS.git
cd FootBall-APIS
