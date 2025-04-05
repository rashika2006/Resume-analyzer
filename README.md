# 🎯 Resume Classifier using NLP & Logistic Regression

Welcome to the **Resume Classifier** project — a machine learning pipeline that uses **Natural Language Processing (NLP)** techniques and a **Logistic Regression model** to automatically classify resumes into job categories like Data Science, HR, Design, and more. This project is perfect for exploring end-to-end NLP workflows and text classification.

---

## 🚀 Features
✨ Highlights of what this project can do:
- 📊 Perform Exploratory Data Analysis (EDA) with visual insights
- 🧹 Clean and preprocess raw resume text
- 🔠 Tokenize and remove stopwords
- 💡 Generate Word Clouds and extract frequent words
- 🔢 Encode labels and extract features using TF-IDF
- 🤖 Train a Logistic Regression model
- 📈 Evaluate model performance with accuracy and classification reports

---

## 📚 Dataset
We use the `UpdatedResumeDataSet.csv` which contains:
- **`Category`**: The job domain of the resume (e.g., HR, Data Science, Design)
- **`Resume`**: Raw text data of resumes

📁 Place this file inside a folder named `data/` in your project directory.

---

## ⚙️ Getting Started
Follow these steps to run the project locally:

### 🛠️ 1. Clone the Repository
```bash
git clone https://github.com/yourusername/resume-classifier.git
cd resume-classifier
```

### 🧪 2. Set Up a Virtual Environment (Optional)
```bash
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
```

### 📦 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 🚀 4. Run the Application
```bash
python main.py
```

---

## 📊 Visual Results
Get insights into your data and model using the following visualizations:

### 🎯 Resume Category Distribution
Visual breakdown of the number of resumes per job category:
![Category Plot](assets/category_plot.png)

### 📝 Word Count Distribution
Histogram of the number of words in resumes:
![Word Count Plot](assets/wordcount_hist.png)

### ☁️ Word Cloud of Frequent Words
Visual representation of most used keywords:
![Word Cloud](assets/wordcloud.png)

### 🔡 Top 50 Frequent Words
Bar chart showing most common meaningful words across resumes:
![Top Words Bar Plot](assets/top_words_bar.png)

### 📉 Classification Report (Sample Output)
Performance summary of the trained model:
```
              precision    recall  f1-score   support

      DESIGN       0.88      0.90      0.89        20
 DATA SCIENCE     0.95      0.92      0.94        25
         HR       0.85      0.88      0.86        18
        ...
```

---

## 📦 Requirements
All required packages are listed in `requirements.txt`:
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `nltk`, `wordcloud`
- `scikit-learn`

---

## 🤝 Contributions
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📬 Contact
For questions or collaboration:
- 📧 Email: rashikajainlko@gmail.com
- 🌐 GitHub: https://github.com/rashika2006

---

## 📄 License
This project is licensed under MIT License

---


