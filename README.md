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


git clone https://github.com/DarshanKagude/FootBall-APIS.git
cd FootBall-APIS

##2.Set Up a Virtual Environment (Optional but Recommended)
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

###3. Install Required Python Packages
pip install flask flask-cors requests

###4. Add Your API Key
headers = {
    'x-rapidapi-key': "YOUR_RAPIDAPI_KEY",
    'x-rapidapi-host': "free-api-live-football-data.p.rapidapi.com"
}

###5. Run the Flask Application
python app.py
