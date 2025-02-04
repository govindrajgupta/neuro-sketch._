

# 🎨 NeuroSketch: The AI-Powered Calculator 🧮

NeuroSketch is an AI-powered calculator that brings your drawings to life, inspired by the innovative iPad Math Notes/Calculator application. This project is designed for both beginners and experienced developers looking to enhance their skills in AI and web development.

---

## 🚀 Features
- 🎨 Handwritten math recognition
- 🤖 AI-powered calculations using Google Gemini API
- 🏗️ Built with FastAPI (Backend) & React (Frontend)
- 🖼️ Image processing using PIL
- 🌐 Real-time rendering

---

## 🛠️ Tech Stack
### **Frontend:**
- React.js
- TypeScript
- Axios for API requests

### **Backend:**
- FastAPI
- Python
- Google Gemini API
- PIL for image processing

### **Other Dependencies:**
- dotenv (for environment variables)
- CORS Middleware (for cross-origin requests)

---

## 🏗️ Installation & Setup
### **1️⃣ Clone the Repository**
```sh
 git clone https://github.com/your-username/mathcanvas.git
 cd mathcanvas
```

### **2️⃣ Backend Setup**
```sh
 cd calc-be
 python -m venv venv  # Create Virtual Environment
 source venv/bin/activate  # (Linux/Mac)
 venv\Scripts\activate  # (Windows)
 pip install -r requirements.txt  # Install Dependencies
```

### **3️⃣ Set Up API Key**
Create a `.env` file inside `calc-be/` and add:
```sh
 GEMINI_API_KEY=your_api_key_here
```

### **4️⃣ Start the Backend Server**
```sh
 uvicorn main:app --host 0.0.0.0 --port 8900 --reload
```

### **5️⃣ Frontend Setup**
```sh
 cd ../calc-fe
 npm install  # Install Dependencies
 npm run dev  # Start Frontend
```

---

## 🔥 Usage
1. Open the frontend in your browser.
2. Draw mathematical expressions.
3. Submit to see AI-powered calculations in action!

---

## 🛠️ Troubleshooting
- **ModuleNotFoundError?** Run `pip install -r requirements.txt` in `calc-be`
- **404 Error on `/calculate`?** Ensure backend is running at `http://localhost:8900`
- **CORS Issues?** Add CORS middleware to FastAPI.

---

## 📌 Future Enhancements
- 🔢 Support for more complex mathematical equations
- 🎨 Improved handwriting recognition
- 📱 Mobile-friendly UI

---

## 📧 Contact
For any issues or feature requests, feel free to reach out or open a GitHub issue!

🌟 **Enjoy building NeuroSketch!** 🌟

