
# 📘 Automated Answer Sheet Assessment System using LLMs  

🚀 **Final Year Project (FYP)** — Developed to automate the evaluation of handwritten student answer sheets using **Artificial Intelligence (AI)** and **Large Language Models (LLMs)**.  

This system integrates **OCR models, rubric-based grading**, and **semantic evaluation through LLMs** to make assessments faster, fairer, and more scalable for educators.  

---

## ✨ Key Features  

### 📝 Handwritten Text Recognition (OCR)  
Integrated with multiple **OCR and Vision-Language models** for highly accurate handwritten text extraction:
- **GPT-4o-mini (Paid)** – used for benchmark-level performance testing.  
- **GPT-4o-mini (Azure Free Tier)** – accessed via GitHub Marketplace for experiments.  
- **LLaMA 3.2 11B Vision-Instruct** – open-source model deployed on Azure.  
- **H2O VL-Mississippi** – hosted via Google Colab GPU and served through **ngrok + Flask API**.  

➡️ A **Flask backend server** processes `base64-encoded images` along with a **question prompt**, returning structured answers ready for AI-based evaluation.  

---

### 📊 Rubric-Based Evaluation  
- Teachers can upload **custom grading rubrics**.  
- Ensures **standardized and unbiased scoring**.  
- Allows **flexible weighting** of different assessment criteria.  

---

### 🤖 AI Evaluation (Gemini-based)  
- Uses **semantic and context-aware scoring**, going beyond simple keyword matching.  
- Evaluates clarity, completeness, and relevance of handwritten answers.  

---

### 📄 Auto-Generated Reports  
- Produces **automated .docx reports** for each student.  
- Includes question-wise marks, detailed feedback, and overall summary.  

---

### 🔗 Tech Stack  

| Layer | Technology |
|-------|-------------|
| **Frontend** | React.js |
| **Backend** | Node.js + Express + Flask (OCR & AI services) |
| **Database** | MongoDB Atlas |
| **Authentication** | Firebase Authentication |
| **Model Hosting** | Google Colab + ngrok + Azure Marketplace |
| **AI Models** | GPT-4o-mini, LLaMA 3.2, H2O VL-Mississippi, Gemini |

---

## 🧠 My Contribution  
- Implemented the **AI evaluation module** using LLMs for rubric-based scoring.  
- Integrated **Flask API** with OCR services and Colab-based models.  
- Designed the **automation pipeline** for report generation and data processing.  
- Collaborated in **system architecture and testing** for deployment stability.  

--


---

## 🌟 Future Work  
- Integration of handwriting segmentation for line-level accuracy.  
- Development of a dashboard for teacher analytics.  
- Support for multilingual handwritten text recognition.  
- Fine-tuned rubric evaluation model with domain-specific training.  

---

## 📧 Contact  
For inquiries or collaborations:  
**📩 Email:** fardeenkhanmahar1@gmail.com  
**🌐 GitHub:** [Fardeen Khan](https://github.com/FardeenKhan0070)

---

⭐ *If you found this project interesting, don’t forget to star the repository!*  


