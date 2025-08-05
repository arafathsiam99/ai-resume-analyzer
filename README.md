# 🧠 AI Resume Analyzer

![License](https://img.shields.io/github/license/arafathsiam99/ai-resume-analyzer?style=flat-square)
![Stars](https://img.shields.io/github/stars/arafathsiam99/ai-resume-analyzer?style=flat-square)
![Issues](https://img.shields.io/github/issues/arafathsiam99/ai-resume-analyzer?style=flat-square)

Analyze resumes with LLM-powered insights — detect gaps, improve wording, and get AI feedback.

---

## 🔗 Live Demo

🌍 [ai-resume-analyzer.vercel.app](https://ai-resume-analyzer.vercel.app)  
📁 [View the Project Repository](https://github.com/arafathsiam99/ai-resume-analyzer)

---

## ⚙️ Tech Stack

- **Frontend**: React 19, Tailwind CSS, React Dropzone
- **Backend**: Node.js, React Router (Server-side rendering)
- **AI**: OpenAI GPT-4 (via API)
- **PDF Parsing**: `pdfjs-dist`
- **State Management**: Zustand

---

## 💡 Why I Built This

As AI continues to reshape job markets, I wanted to build a tool that:

- Helps job seekers **optimize resumes** using real-time AI feedback
- Offers insights on **tone, gaps, strengths**, and **clarity**
- Bridges the gap between static resumes and intelligent resume understanding

---

## ✨ Key Features

- 📄 **Drag-and-drop PDF Resume Upload**
- 🧠 **LLM-Powered Resume Summary and Suggestions**
- 🔍 **Category-wise Analysis** (Experience, Skills, Formatting, etc.)
- ⚡ Fast and lightweight — deploys in seconds on Vercel
- 🌙 Dark mode support for comfortable reading

---

## 🚀 How to Use

### 📦 Local Setup

```bash
# 1. Clone the repo
git clone https://github.com/arafathsiam99/ai-resume-analyzer

# 2. Install dependencies
npm install

# 3. Add your OpenAI API key
# Create a .env file and include:
OPENAI_API_KEY=your-key-here

# 4. Run the app locally
npm run dev
