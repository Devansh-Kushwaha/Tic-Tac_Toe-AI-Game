# 🎮 Tic-Tac-Toe AI Game

A full-stack Tic-Tac-Toe AI game built using **Django REST Framework** for the backend and **React** for the frontend.  
The AI uses the **Minimax algorithm** with difficulty levels, offering a fun and challenging experience for all players.

---

## 🚀 Features
- 🤖 AI-powered gameplay with Easy, Medium, and Hard modes  
- 🧠 Minimax-based decision-making  
- 🎨 Interactive and modern React UI  
- 🔁 Real-time board updates via API calls  
- 🌐 Easily deployable locally using **ngrok**

---

## 🏗️ Tech Stack
### Frontend
- React JS  
- HTML5 / CSS3  

### Backend
- Django REST Framework  
- Python  

---

## 📂 Folder Structure
```
Tic-Tac-Toe AI Game/
│
├── tic_tac_toe_ai/           # Django Backend
│   ├── game/                 # Game logic and API
│   ├── manage.py
│   └── ...
│
└── tic-tac-toe-frontend/     # React Frontend
    ├── src/
    ├── public/
    └── package.json
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/tic-tac-toe-ai-game.git
cd tic-tac-toe-ai-game
```

### 2️⃣ Backend Setup
```bash
cd tic_tac_toe_ai
pip install -r requirements.txt
python manage.py runserver
```
Backend runs by default on `http://127.0.0.1:8000/`

### 3️⃣ Frontend Setup
```bash
cd ../tic-tac-toe-frontend
npm install
npm start
```
Frontend runs by default on `http://localhost:3000/`

---

## 🌍 Public Access via Ngrok
To make your app accessible over the internet:
```bash
ngrok http 3000   # Expose frontend
ngrok http 8000   # Expose backend
```
Update the backend API URL inside your React app (`App.jsx`) with your ngrok backend URL.

---

## 🧩 API Endpoint
**POST** `/game/move/`  
Handles player and AI moves, returning the updated board and game result.

---

## 👨‍💻 Author
**Devansh Kushwaha**  
🎓 Final-year B.Tech CSE student at IIIT Surat  
💡 Passionate about AI, Web Development, and Game Logic Design.

---

## 🪪 License
This project is open-source and available under the [MIT License](LICENSE).
