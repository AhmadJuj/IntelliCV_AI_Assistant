# 🤖 IntellicV – AI Resume Assistant

**IntellicV** is an AI-powered resume builder and assistant built using the **MERN Stack** and **GPT integration**.  
It helps users **create**, **enhance**, and **update** resumes intelligently with AI-suggested improvements, modern templates, and instant PDF downloads — all within a sleek, responsive interface.

---

## ✨ Key Features

### 🧠 AI Resume Enhancement
- Uses **OpenAI GPT** to improve resume content with better tone, clarity, and phrasing  
- Supports real-time suggestions for skill additions, bullet restructuring, and experience optimization  
- Chat-based AI assistant to dynamically update resume fields  

### 🧩 Smart Resume Editing
- Inline resume editing — update any section instantly  
- Auto-saves progress when logged in  
- Add, remove, or modify resume sections through the chat interface  

### 🎨 Professional Templates
- 3–4 **modern, responsive resume templates**  
- Preview resumes live with different layouts and color schemes  
- Optimized for both screen and A4 PDF formats  

### 📄 PDF Download
- Instant **A4 PDF download** of selected template  
- Proper formatting and font consistency for professional output  

### 🔐 Authentication & Data Persistence
- User signup and login with secure JWT authentication  
- Save and manage multiple resume versions in your account  

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | React.js (Vite) + Tailwind CSS |
| Backend | Node.js + Express.js |
| Database | MongoDB |
| AI Integration | OpenAI GPT API |
| State Management | React Hooks + Context API |
| Authentication | JWT (JSON Web Token) |
| File Generation | html2pdf / jsPDF |
| Deployment | Render / Vercel |

---

## ⚙️ Setup & Installation

### Prerequisites
Ensure you have installed:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/intellicv.git
   cd intellicv
````

2. **Install dependencies**

   ```bash
   npm install
   cd client
   npm install
   cd ..
   ```

3. **Configure environment variables**
   Create a `.env` file in the root directory:

   ```bash
   MONGO_URI=your_mongodb_connection
   OPENAI_API_KEY=your_openai_api_key
   JWT_SECRET=your_secret
   VITE_API_URL=http://localhost:5000
   ```

4. **Run the development servers**

   ```bash
   # Start backend
   npm run server

   # Start frontend
   cd client
   npm run dev
   ```

5. **Access the app**
   Open [http://localhost:5173](http://localhost:5173) in your browser.


## 🧠 Future Improvements

* Add AI-powered **job description matching**
* Include **LinkedIn import** and **ATS compatibility checker**
* Introduce **multi-language resume support**
* Enable **real-time collaboration** (shared editing)

---
