# Sentiment Analysis using NLP

This project performs **Sentiment Analysis on movie reviews** using **Natural Language Processing (NLP)** and **Machine Learning**.  
The model predicts whether a given movie review expresses **Positive or Negative sentiment**.

---

## 📌 Features
- Text preprocessing using **NLTK**
- Stopword removal and **Lemmatization**
- Feature extraction using **TF-IDF Vectorizer**
- Sentiment classification using **Logistic Regression**
- Predict sentiment for new user input text

---

## 🛠️ Technologies Used
- Python
- NLTK
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression

---

## ⚙️ Project Workflow

1. **Text Preprocessing**
   - Convert text to lowercase  
   - Tokenization  
   - Remove stopwords  
   - Apply lemmatization  

2. **Feature Extraction**
   - Convert cleaned text into numerical vectors using **TF-IDF**

3. **Model Training**
   - Split dataset into training and testing sets  
   - Train the model using **Logistic Regression**

4. **Evaluation**
   - Predict sentiment on test data  
   - Calculate model accuracy

5. **Prediction**
   - Input a new movie review  
   - Model predicts the sentiment

---

## 📊 Example

Input:
```
This movie is amazing and I really liked it.
```
Output:
```
Sentiment: Positive
```
---
## 📂 Project Structure
```
sentiment-analysis-nlp
│
├── sentiment_analysis.py
├── dataset.csv
├── README.md
```
---

## 🚀 Future Improvements
- Implement **Deep Learning models (LSTM / BERT)**
- Build a **Streamlit web application**
- Improve model performance with larger datasets
---
## 👨‍💻 Author
**Tanuj Kumar**  
B.Tech CSE (AI & ML)  
Skills: Python | Machine Learning | NLP | Deep Learning | Data Science
🔗 GitHub: https://github.com/tanujkumarpandranki/movie-review-sentiment-analysis
