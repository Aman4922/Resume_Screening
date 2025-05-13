# 📝 Resume Screening

A machine learning project designed to automate the process of screening resumes based on job descriptions using Natural Language Processing (NLP).

## 🔍 Overview
This project helps HR teams and recruiters by ranking or classifying resumes based on their relevance to specific job descriptions. It extracts textual features from resumes and compares them with job requirements using NLP techniques.

## 🛠️ Tech Stack
- **Python**
- **Libraries:** Pandas, NumPy, NLTK / SpaCy, Scikit-learn, TfidfVectorizer
- **Model:** Logistic Regression / SVM / Cosine Similarity

## 📂 Features
- Text cleaning and preprocessing (removing stopwords, lemmatization)
- Feature extraction using TF-IDF or embeddings
- Resume vs. Job Description similarity matching
- Classification of resumes as relevant or not
- Ranking resumes based on similarity scores

## 📊 Output
- List of matched resumes with similarity percentages
- Optionally, save results in a CSV file or visualize match quality

## 📁 Dataset
- Custom resumes and job descriptions in `.txt` or `.pdf` format
- Optionally anonymized data for privacy

## 🚀 How to Run
1. Clone the repo  
2. Add your resumes and job descriptions to the `/data` folder  
3. Run `python Resume_Screening.py`  
4. View ranked output in terminal or output file

## 📌 Future Improvements
- Support for PDF parsing
- Integration with a web interface
- More advanced embeddings (BERT, Word2Vec)

