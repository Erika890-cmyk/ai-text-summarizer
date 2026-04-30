# 🧠 AI Text & PDF Summarizer

A full-stack web application that summarizes text and PDF documents using AI.
Built with modern web technologies and integrated with AI APIs for real-time summarization.

---

## 🚀 Features

* ✏️ Summarize plain text instantly
* 📄 Upload and summarize PDF files
* 📥 Download summary as PDF
* ⚡ Fast and responsive UI
* 🎨 Clean and modern design

---

## 🏗️ Tech Stack

**Frontend**

* React.js
* Axios
* CSS (Custom Styling)

**Backend**

* Node.js
* Express.js
* Multer (File Upload)
* pdf-parse (PDF Extraction)

**AI Integration**

* OpenAI API

---

## 📸 Screenshot

<img width="631" height="638" alt="ai_text" src="https://github.com/user-attachments/assets/886f4d31-1cd1-45bb-aa48-6aedfe48e786" />


---

## ⚙️ Run Locally

### 1️⃣ Clone Repository

```
git clone https://github.com/your-username/ai-text-summarizer.git
cd ai-text-summarizer
```

---

### 2️⃣ Setup Backend

```
cd backend
npm install
node server.js
```

---

### 3️⃣ Setup Frontend

```
cd frontend
npm install
npm start
```

---

## 🔑 Environment Variables

Create a `.env` file inside the backend folder:

```
OPENAI_API_KEY=your_api_key_here
```

---

## 📌 API Endpoints

| Method | Endpoint   | Description              |
| ------ | ---------- | ------------------------ |
| POST   | /summarize | Summarize text input     |
| POST   | /upload    | Upload and summarize PDF |

---

## 💡 Future Improvements

* 🌐 Multi-language summarization
* 📊 Word count & analytics
* 💬 Chat with PDF
* 🔐 User authentication

---

## 📄 License

This project is licensed under the MIT License.
