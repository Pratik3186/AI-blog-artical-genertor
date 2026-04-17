# 🧠 AI Blog Article Generator

An intelligent web application that automatically generates high-quality blog articles using Generative AI. This project leverages modern LLMs to transform user input into well-structured, readable, and SEO-friendly content.

---

## 🚀 Features

- ✍️ Generate blog articles from a simple topic or prompt  
- 🧠 Powered by Generative AI (LLMs)  
- ⚡ Fast and responsive UI  
- 📄 Structured output (Title, Headings, Content)  
- 🔍 SEO-friendly content generation  
- 📋 Copy/download generated articles  
- 🔐 (Optional) User authentication system  

---

## 🛠️ Tech Stack

### Frontend
- React.js  
- HTML5, CSS3  
- Bootstrap / Tailwind (optional)

### Backend
- Python  
- Django  (backend) 

### AI & Tools
- OpenAI / Google Generative AI API  
- LangChain (optional)  
- python-dotenv  

---

## 📂 Project Structure

```
AI-Blog-Article-Generator/
│
├── frontend/              # React frontend
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/               # Django backend
│   ├── blog_generator/
│   ├── api/
│   ├── manage.py
│   └── requirements.txt
│
├── .env                   # Environment variables
├── README.md
└── .gitignore
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/ai-blog-article-generator.git
cd ai-blog-article-generator
```

---

### 2️⃣ Backend Setup (Django)

```bash
cd backend
python -m venv venv

# Activate environment
# Linux / Mac
source venv/bin/activate

# Windows
venv\Scripts\activate

pip install -r requirements.txt
```

Create a `.env` file in backend folder:

```
API_KEY=your_api_key_here
```

Run backend server:

```bash
python manage.py runserver
```

---

### 3️⃣ Frontend Setup (React)

```bash
cd frontend
npm install
npm start
```

---

## 🔄 How It Works

1. User enters a blog topic  
2. Frontend sends request to backend API  
3. Backend processes prompt  
4. AI model generates structured article  
5. Response is sent back to frontend  
6. User views/downloads the article  

---

## 📸 Example Input

```
Topic: "Future of Artificial Intelligence in Healthcare"
```

---

## 📄 Output

- Title  
- Introduction  
- Headings  
- Detailed content  
- Conclusion  

---

## 🔐 Environment Variables

| Variable | Description        |
|----------|--------------------|
| API_KEY  | AI model API key   |

---

## 📈 Future Improvements

- 🧾 Blog saving system (database)  
- 🧑‍💻 User dashboard  
- 🌐 Multi-language support  
- 🎯 Tone customization  
- 📊 SEO scoring system  

---

## 🤝 Contributing

Contributions are welcome!

```
fork → clone → create branch → commit → push → pull request
```

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Pratik**  
BTech CSE | Aspiring Developer & Researcher
