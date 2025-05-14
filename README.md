# 💼 CV Information Extractor with Phi-3 Mini

> AI-powered resume parser using Microsoft's Phi-3 Mini model  
> 📄 → 🧠 → 📊 | From raw PDF to structured data in seconds

## 📌 Project Overview

This project is an end-to-end tool for extracting structured information from CVs (in PDF format) using **Large Language Models**. With the help of **Microsoft's Phi-3 Mini**, it can intelligently identify and summarize the most important parts of a resume.

## 🧪 Step-by-Step Pipeline

| Step | Description |
|------|-------------|
| **1. Upload CV** | Upload a `.pdf` file containing a candidate's resume |
| **2. CV Reader** | Use `PyMuPDF` to extract raw text from the uploaded PDF |
| **3. Text Cleaning** | Clean the text using `NLTK` and standard Python (lowercasing, punctuation, stopword removal) |
| **4. Model Load** | Load Microsoft's `Phi-3 Mini 4K Instruct` model from Hugging Face using PyTorch |
| **5. Prompt Creation** | Create a structured prompt for information extraction |
| **6. Text Generation** | Use the model to generate structured JSON-style output containing name, email, skills, etc. |
| **7. Output Display** | Print or return the extracted structured data |

## 🛠️ Technologies Used

- **Google Colab** – For quick and GPU-accelerated experimentation  
- **PyMuPDF (`fitz`)** – PDF text extraction  
- **NLTK** – Natural Language Toolkit for preprocessing  
- **Hugging Face Transformers** – Interface to load Phi-3 Mini  
- **PyTorch** – Deep learning backend  
- **Phi-3 Mini 4K Instruct** – Lightweight and powerful LLM from Microsoft  

## 🚀 Try it Out

1. Open the notebook in Google Colab:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Resul-Caliskan/CV-Extraction-Ai/blob/main/CV_Extraction_Ai.ipynb)

2. Run each cell step-by-step  
3. Upload a resume PDF when prompted  
4. View structured data (name, email, phone, skills, experience, etc.)  

## 🧠 Extracted Information Includes

```json
{
  "name": "",
  "email": "",
  "phone": "",
  "skills": "",
  "languages": "",
  "experience": ""
}
```

## 🔮 Planned Features

- Match resumes to job descriptions
- Batch CV analysis
- Multilingual support (e.g., Turkish)
- Export results to CSV or JSON

## 📄 License

This project is licensed under the MIT License. Feel free to use, modify, and build upon it for personal or commercial purposes.

## 🙋‍♂️ Author

Resul Çalışkan  
🤖 AI Enthusiast
🔗 GitHub: [Resul-Caliskan](https://github.com/Resul-Caliskan)
🔗 Linkedin: [Resul-Caliskan](https://www.linkedin.com/in/resul-caliskan/)
