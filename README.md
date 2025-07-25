## Hi there 👋 <h1 align="center">📄 AI Resume Builder</h1>
<h3 align="center">A Streamlit-based web app for uploading, parsing, scoring, and enhancing resumes using NLP & LLMs</h3>

---

### 💡 About the Project

This project is a complete pipeline for resume processing. It enables users to:

✅ Upload their resume (PDF or DOCX)  
✅ View a live preview of the file  
✅ Parse education, experience, and skills using NLP  
✅ Calculate ATS (Applicant Tracking System) score  
✅ Suggest improvements using AI/LLM models

---

### 🔧 Tech Stack

- *Frontend*: Streamlit  
- *Backend*: Python  
- *Libraries*: spaCy, pdfminer, docx, pandas  
- *LLM APIs*: OpenAI / Groq / OpenRouter  
- *Version Control*: Git & GitHub

---

### 📂 Folder Structure

```bash
├── frontend/        # Streamlit UI
├── backend/         # LLM integration
├── scoring/         # ATS scoring logic
├── nlp/             # Resume parsing (spaCy)
├── data/            # Sample resumes
├── utils/           # Helper functions
├── README.md
├── requirements.txt
└── .gitignore
