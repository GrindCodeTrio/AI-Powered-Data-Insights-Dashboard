# AI-Powered Data Insights Dashboard

🚀 A full-stack AI-powered data dashboard with **React (Vite) + Flask + PostgreSQL + AI/ML Integration** for real-time insights, anomaly detection, and interactive visualizations.

---

## 🔹 Features
✅ **User & Admin Dashboards** with JWT & OAuth Authentication  
✅ **Data Upload** (CSV/Excel) & AI-Based Analysis  
✅ **ML/NLP Integration** (Hugging Face, GPT-4, Anomaly Detection)  
✅ **Interactive Visualizations** (Recharts, D3.js, Plotly)  
✅ **Export Data** (CSV, PDF Reports)  

---

## 📦 Tech Stack

### **Frontend:**
- 🖥️ **React + Vite** (Fast UI Rendering)
- 🎨 **Tailwind CSS + ShadCN** (Modern UI Components)
- 📊 **Recharts / D3.js / Plotly.js** (Data Visualization)
- 🔑 **OAuth2 + JWT Auth** (Google, GitHub Login)

### **Backend:**
- 🚀 **Flask + Flask-CORS** (REST API)
- 🧠 **AI APIs (Hugging Face, OpenAI, Google Vertex AI)** (AI-powered insights)
- 📊 **Matplotlib + Seaborn + Plotly** (Data Analytics & Visualization)
- 🔗 **PostgreSQL + SQLAlchemy** (Database)
- 📂 **Pandas + OpenPyXL** (Data Processing)
- 📑 **ReportLab + xhtml2pdf** (PDF Report Generation)

---

## 🛠️ Installation & Setup

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/ai-dashboard.git
cd ai-dashboard
```

### **2️⃣ Backend Setup (Flask)**
```bash
cd backend
python3 -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

### **3️⃣ Frontend Setup (React + Vite)**
```bash
cd frontend
npm install
npm run dev
```

---

## 📊 API Endpoints

| Method | Endpoint | Description |
|--------|---------|-------------|
| **POST** | `/api/auth/login` | User Login (JWT) |
| **POST** | `/api/auth/signup` | User Signup |
| **POST** | `/api/data/upload` | Upload Dataset |
| **GET** | `/api/data/analyze` | AI-based Data Analysis |
| **GET** | `/api/data/export/csv` | Export Data as CSV |
| **GET** | `/api/data/export/pdf` | Export Data as PDF |

---

## 🚀 Deployment
### **Backend (Flask)**
- **Docker:**  
```bash
docker-compose up --build
```
- **Render/Railway:** Push Flask API to hosting

### **Frontend (React)**
- **Vercel:** `vercel deploy`  
- **Netlify:** `npm run build && netlify deploy`  

---

## 📜 License
MIT License  

---

## 💡 Future Enhancements
🔹 Add WebSockets for **Live AI Insights**  
🔹 Integrate **Custom AI Models** (instead of API-based AI)  
🔹 Improve **Anomaly Detection** with PyOD & Isolation Forest  




