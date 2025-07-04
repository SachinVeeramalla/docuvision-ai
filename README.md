# 🚀 DocuVision AI
**Intelligent Document Summarization & Risk Analysis Platform**

DocuVision AI automatically ingests documents, extracts text using OCR, summarizes content with AI, and flags potential risks — turning unstructured documents into actionable insights.

---

## 📌 What it does

✅ Upload scanned PDFs or images of documents  
✅ Extracts text with Tesseract OCR  
✅ Generates summaries using Hugging Face Transformers or OpenAI API  
✅ Flags potential risks with keyword-based or ML classification  
✅ Answers document-specific questions (planned)  
✅ User-friendly React/Next.js dashboard to display results  

---

## 🛠️ Tech Stack

- **Backend**: FastAPI (Python), Tesseract OCR, Hugging Face Transformers or OpenAI API  
- **Database**: Supabase (PostgreSQL) or self-hosted PostgreSQL (SQLAlchemy)  
- **Frontend**: Next.js (React) with TailwindCSS  
- **Infrastructure**: Docker, Docker Compose, AWS S3 (optional for file storage)

---

## 🔑 AI Tasks Planned

✅ Document Summarization  
✅ Text Classification (risk scoring)  
✅ Document Question Answering  
✅ Visual Question Answering (optional future milestone)

---

## 🚦 Milestones

- [x] 📂 Project structure & repo setup  
- [x] 📝 FastAPI file upload API  
- [ ] 🔍 OCR pipeline with Tesseract  
- [ ] 🧠 Summarization integration (Hugging Face/OpenAI)  
- [ ] ⚠️ Risk classification module  
- [ ] 💻 Next.js frontend dashboard  
- [ ] 📦 Deployment with Docker Compose  

---

## ⚙️ Architecture

```plaintext
[User]
   ⬇️ upload document
[Next.js Frontend]
   ⬇️ calls
[FastAPI Backend]
   ⬇️ process
OCR & AI Summarization & Risk Analysis
   ⬇️ store metadata/results
[Supabase/PostgreSQL Database]
