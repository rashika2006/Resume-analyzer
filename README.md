# 📄 Resume Classifier using NLP and Logistic Regression

This project is a resume classification system that leverages Natural Language Processing (NLP) and a Logistic Regression model to categorize resumes into predefined job roles such as Data Science, HR, Design, and more.

---

## 🚀 Features
- Exploratory Data Analysis (EDA) and visualizations
- Text preprocessing and cleaning
- Word cloud and word frequency analysis
- Label encoding for target categories
- TF-IDF vectorization of resume text
- Logistic Regression classifier
- Evaluation using accuracy and classification report

---

## 📚 Dataset
The dataset used is `UpdatedResumeDataSet.csv` containing two columns:
- `Category`: The job category the resume belongs to
- `Resume`: Raw text of the resume

You can place this file in a `data/` folder in your project directory.

---

## ⚙️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/resume-classifier.git
cd resume-classifier
```

### 2. Create a Virtual Environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate
```

### 3. Install Requirements
```bash
pip install -r requirements.txt
```

### 4. Run the Project
```bash
python main.py
```

---

## 🔄 Output Examples
- Resume category distribution bar plot
- Word count histogram of resumes
- WordCloud for most common resume terms
- Model accuracy on test set
- Classification report (precision, recall, F1-score per category)

---

## 📆 Dependencies
All dependencies are listed in the `requirements.txt` file, including:
- pandas, numpy
- matplotlib, seaborn
- nltk, wordcloud
- scikit-learn

---

## ✉️ Contact
For questions or contributions, feel free to open an issue or submit a pull request.

---

## ✉️ License
This project is open-source. Add your preferred license file (e.g., MIT, Apache 2.0).

