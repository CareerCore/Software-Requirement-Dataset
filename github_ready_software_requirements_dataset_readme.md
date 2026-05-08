# 📘 Software Requirements Dataset

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-NLP-green.svg)
![License](https://img.shields.io/badge/License-Kaggle-orange.svg)

## 📌 Overview
This project focuses on analyzing and classifying software requirements using Natural Language Processing (NLP) and Machine Learning techniques.

The dataset contains software requirement statements categorized into Functional and Non-Functional Requirements. The project can be used for text classification, software engineering research, and AI-based requirement automation systems.

---

## 📂 Dataset Information
- **Dataset Source:** Kaggle
- **Dataset Type:** Text Classification
- **Domain:** Software Engineering / NLP
- **File Format:** CSV

### Dataset Features
| Column | Description |
|---|---|
| `Type` | Requirement category label |
| `Requirement` | Requirement statement text |

---

## 🏷️ Requirement Categories
The dataset includes the following categories:

- Functional (F)
- Functional Requirement (FR)
- Non-Functional Requirement (NFR)
- Availability (A)
- Fault Tolerance (FT)
- Legal (L)
- Look & Feel (LF)
- Maintainability (MN)
- Operational (O)
- Performance (PE)
- Portability (PO)
- Scalability (SC)
- Security (SE)
- Usability (US)

---

## 🎯 Project Objectives
- Analyze software requirement statements
- Perform text preprocessing and NLP tasks
- Build machine learning classification models
- Predict requirement categories automatically
- Improve software requirement management systems

---

## ⚙️ Technologies Used
- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- NLTK / SpaCy
- Matplotlib
- Seaborn

---

## 🔍 Project Workflow

### 1️⃣ Data Collection
Load the dataset from Kaggle.

### 2️⃣ Data Preprocessing
- Remove stopwords
- Tokenization
- Text cleaning
- Lemmatization / Stemming

### 3️⃣ Exploratory Data Analysis (EDA)
- Requirement distribution
- Word frequency analysis
- Word clouds
- Data visualization

### 4️⃣ Feature Engineering
- TF-IDF Vectorization
- Count Vectorizer

### 5️⃣ Model Building
Possible models:
- Naive Bayes
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)

### 6️⃣ Model Evaluation
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 📊 Applications
This project can be used in:

- Requirement classification systems
- NLP-based software engineering tools
- AI-driven requirement automation
- Academic research projects
- Requirement analysis platforms

---

## 🚀 Installation & Usage

### Clone Repository
```bash
git clone https://github.com/your-username/software-requirements-dataset.git
```

### Navigate to Project Folder
```bash
cd software-requirements-dataset
```

### Install Dependencies
```bash
pip install pandas numpy scikit-learn nltk spacy matplotlib seaborn
```

### Run the Project
```bash
python main.py
```

---

## 📁 Suggested Project Structure
```bash
software-requirements-dataset/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── training.py
│   └── evaluation.py
│
├── models/
│
├── requirements.txt
├── README.md
└── main.py
```

---

## 📈 Future Improvements
- Deep Learning models (LSTM, BERT)
- Advanced NLP preprocessing
- Requirement summarization
- Requirement generation using AI
- Deployment using Flask or Streamlit

---

## 🤝 Contribution
Contributions are welcome!

If you would like to improve this project:
1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Submit a pull request

---

## 📜 License
This dataset belongs to its respective Kaggle owner.

Please check the original dataset license before commercial use.

---

## 📧 Contact
For any questions or collaboration:
- GitHub: your-username
- Kaggle: Kaggle Profile

---

⭐ If you found this project useful, give it a star on GitHub!

