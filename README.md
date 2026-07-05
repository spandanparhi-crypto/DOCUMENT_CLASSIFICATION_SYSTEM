# 📄 Document Classification System

> **An AI-powered Document Classification System that automatically categorizes documents using OCR, NLP, and Machine Learning.**

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Python](https://img.shields.io/badge/Python-3.10+-yellow.svg)
![Flask](https://img.shields.io/badge/Flask-Backend-green.svg)
![AI](https://img.shields.io/badge/AI-Document%20Classification-red.svg)
![Status](https://img.shields.io/badge/Status-Active-success)

---

# 🚀 Live Demo

🔗 **Live Project:** https://principal-white-ivthfmrd.edgeone.dev/


## 📖 Overview

The **Document Classification System** is an intelligent web application that automatically classifies uploaded documents into predefined categories. It uses **OCR (Optical Character Recognition)** to extract text from scanned documents and **Machine Learning/NLP** models to determine the document type.

The system minimizes manual document sorting, improves productivity, and helps organizations efficiently manage digital documents.

---

## ✨ Features

- 📂 Drag & Drop File Upload
- 📄 PDF Support
- 🖼️ Image Support (PNG, JPG, JPEG)
- 📝 DOCX Support
- 📊 Excel & CSV Support
- 📃 TXT File Support
- 🤖 AI-Based Document Classification
- 🔍 OCR Text Extraction
- 📈 Confidence Score
- 📚 Classification History
- 📥 Download Classification Report
- 🌙 Dark Mode
- ✨ Glassmorphism UI
- 🎨 Animated Dashboard
- 📱 Fully Responsive Design
- 🔒 Secure File Upload

---

# 📁 Supported File Types

| File Type | Supported |
|-----------|-----------|
| PDF | ✅ |
| DOCX | ✅ |
| JPG | ✅ |
| PNG | ✅ |
| JPEG | ✅ |
| TXT | ✅ |
| CSV | ✅ |
| XLSX | ✅ |

---

# 📂 Document Categories

- Invoice
- Resume
- Bank Statement
- Contract
- Medical Report
- Legal Document
- Research Paper
- Tax Document
- Insurance Document
- Government Document
- Receipt
- Business Report
- Passport
- Aadhaar
- PAN Card
- Driving License
- Certificates
- Academic Transcript
- Other

---

# 🛠️ Tech Stack

## Frontend

- HTML5
- CSS3
- JavaScript
- Bootstrap
- Tailwind CSS
- Three.js
- GSAP
- Lottie Animation

---

## Backend

- Python
- Flask
- FastAPI

---

## AI / Machine Learning

- Scikit-Learn
- TensorFlow
- PyTorch
- HuggingFace Transformers
- spaCy
- NLTK

---

## OCR

- Tesseract OCR
- EasyOCR

---

## Database

- SQLite
- MySQL
- MongoDB

---

## Cloud Storage

- Firebase Storage
- AWS S3
- Cloudinary

---

# 📂 Project Structure

```text
Document-Classification-System/
│
├── static/
│   ├── css/
│   ├── js/
│   ├── images/
│   ├── animation/
│   └── icons/
│
├── templates/
│   ├── index.html
│   ├── upload.html
│   ├── dashboard.html
│   ├── result.html
│   └── history.html
│
├── uploads/
├── classified_documents/
├── models/
├── utils/
├── dataset/
│
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

# ⚙️ System Workflow

```text
User Uploads Document
        │
        ▼
Validate File
        │
        ▼
OCR Text Extraction
        │
        ▼
Text Cleaning
        │
        ▼
Feature Extraction
        │
        ▼
AI Classification
        │
        ▼
Confidence Score
        │
        ▼
Assign Category
        │
        ▼
Save Result
        │
        ▼
Display Dashboard
```

---

# 🔄 Complete Working Process

## Step 1

Upload Document

Supported formats

- PDF
- DOCX
- Image
- CSV
- TXT
- Excel

↓

## Step 2

File Validation

- File Size
- File Format
- Virus Scan

↓

## Step 3

OCR Engine

Extracts all readable text.

↓

## Step 4

Text Preprocessing

- Lowercase
- Remove Symbols
- Tokenization
- Stopword Removal
- Lemmatization

↓

## Step 5

Feature Engineering

- TF-IDF
- Word2Vec
- BERT Embeddings

↓

## Step 6

Machine Learning Prediction

Available Models

- Logistic Regression
- Random Forest
- Naive Bayes
- SVM
- BERT

↓

## Step 7

Classification

Example

```text
File Name

Invoice_July.pdf

↓

Predicted Category

Invoice

↓

Confidence

98.74%
```

↓

## Step 8

Store Result

Database saves

- Filename
- Category
- Confidence
- Upload Time
- User
- Status

↓

## Step 9

Dashboard

Displays

- Total Documents
- Categories
- AI Accuracy
- Upload History
- Charts
- Analytics

---

# 📊 Dashboard Features

- 📄 Total Documents
- 📁 Total Categories
- 🤖 AI Accuracy
- 📈 Upload Statistics
- 📊 Pie Chart
- 📉 Bar Graph
- 📜 Recent Activity
- 🔍 Search Documents

---

# 🎨 Modern UI Features

- Glassmorphism
- Floating Cards
- Neon Effects
- Animated Background
- AI Robot Animation
- Drag & Drop Upload
- Smooth Page Transitions
- Floating Particles
- Interactive Charts
- Dark Mode
- Responsive Layout

---

# 📷 Screens

- Home
- Upload
- AI Processing
- Dashboard
- Result
- History
- Analytics
- Settings

---

# 🚀 Installation

Clone Repository

```bash
git clone https://github.com/yourusername/document-classification-system.git
```

Go to Project

```bash
cd document-classification-system
```

Install Dependencies

```bash
pip install -r requirements.txt
```

Run Server

```bash
python app.py
```

---

# 🌐 Open Browser

```text
http://localhost:5000
```

---

# 📦 Requirements

```text
Flask
opencv-python
numpy
pandas
tensorflow
torch
transformers
spacy
scikit-learn
easyocr
pytesseract
pdfplumber
python-docx
openpyxl
Pillow
```

Install all packages

```bash
pip install -r requirements.txt
```

---

# 🔐 Security

- Secure Upload
- Authentication
- Authorization
- SQL Injection Protection
- XSS Protection
- CSRF Protection
- Virus Scan
- Encrypted Storage

---

# 📈 Future Improvements

- AI Chat with Documents
- Multi-language OCR
- Voice Search
- Document Summarization
- Duplicate Detection
- Cloud Sync
- Email Notification
- Mobile Application
- REST API
- Batch Classification

---

# 📊 Example Output

```text
----------------------------------------

File Name

Resume_John.pdf

----------------------------------------

Category

Resume

----------------------------------------

Confidence

99.41%

----------------------------------------

Extracted Text

John Doe
Software Engineer
Python
Machine Learning
Experience
Education

----------------------------------------
```

---

# 📌 Process Diagram

```text
                  DOCUMENT CLASSIFICATION SYSTEM

          +-----------------------------------------+
          |          Upload Document                |
          +-------------------+---------------------+
                              |
                              ▼
               +-----------------------------+
               |     File Validation         |
               +-------------+---------------+
                             |
                             ▼
               +-----------------------------+
               | OCR Text Extraction         |
               +-------------+---------------+
                             |
                             ▼
               +-----------------------------+
               | Text Preprocessing          |
               +-------------+---------------+
                             |
                             ▼
               +-----------------------------+
               | Feature Extraction          |
               +-------------+---------------+
                             |
                             ▼
               +-----------------------------+
               | AI Classification Model     |
               +-------------+---------------+
                             |
                             ▼
               +-----------------------------+
               | Confidence Score            |
               +-------------+---------------+
                             |
                             ▼
               +-----------------------------+
               | Assign Category             |
               +-------------+---------------+
                             |
                             ▼
               +-----------------------------+
               | Save into Database          |
               +-------------+---------------+
                             |
                             ▼
               +-----------------------------+
               | Dashboard & Analytics       |
               +-----------------------------+
```

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Add new feature"
```

4. Push branch

```bash
git push origin feature-name
```

5. Create a Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

**Spandan Parhi**

- GitHub: https://github.com/spandanparhi-crypto
- LinkedIn: https://www.linkedin.com/in/spandan-parhi-852011414/

---

## ⭐ Show Your Support

If you found this project useful:

⭐ Star this repository

🍴 Fork the project

📢 Share it with others

Happy Coding! 🚀
