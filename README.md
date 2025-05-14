# 💼 CV Information Extractor (with Phi-3 Mini)

> AI-powered resume analysis tool — Fast and accurate extraction using Microsoft’s Phi-3 Mini model!

---

## 📌 Project Overview

This project is designed to automatically extract structured information from resumes in PDF format using a large language model. Powered by **Microsoft's Phi-3 Mini**, it can identify key details such as:

- 👤 Name  
- 📧 Email  
- 📞 Phone number  
- 🛠️ Skills  
- 🌍 Spoken languages  
- 💼 Work experience  

---

## 🔧 Technologies Used

| Technology                 | Description                                     |
|---------------------------|-------------------------------------------------|
| Google Colab              | Development and testing environment             |
| PyMuPDF (`fitz`)          | Extracts text from PDF files                    |
| NLTK                      | Natural language preprocessing and stopwords    |
| Hugging Face Transformers| Runs the Phi-3 Mini LLM                         |
| PyTorch                   | Backend framework for deep learning             |

---

## 🚀 How to Use

1. Open the notebook in Google Colab:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your_username/cv-extractor-with-phi3/blob/main/phi3_cv_extractor.ipynb)

2. Run the cells and upload a CV in PDF format  
3. The AI will analyze the document  
4. Get the structured output in a JSON-like format

---

## 📦 Features

- ✅ Reads and cleans text from PDF files  
- ✅ Preprocesses input (lowercasing, punctuation removal, stopword filtering)  
- ✅ Extracts structured data using Phi-3 Mini  
- ✅ Optimized for GPU (CUDA) acceleration  

---

## 🧠 Future Improvements

- [ ] Match CVs with job descriptions  
- [ ] Batch processing for multiple resumes  
- [ ] Native support for Turkish CVs  

---

## 📄 License

This project is open-source under the MIT License — feel free to use, modify, and share!

---

