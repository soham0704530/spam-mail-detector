# 📧 Spam Mail Detector

This project classifies SMS messages as **Spam** or **Ham** (Not Spam) using text preprocessing and machine learning.  
It uses the **SMS Spam Collection Dataset** from UCI.

---

## 📊 Workflow
1. Download dataset (`spam.csv`)
2. Explore dataset with graphs
3. Preprocess messages (lowercase, remove stopwords, TF-IDF vectorization)
4. Split into train/test sets
5. Train a Naive Bayes classifier
6. Evaluate using accuracy, classification report, and confusion matrix

---

## 🚀 Results
- Accuracy: ~97%
- Model: Multinomial Naive Bayes

---

## 📂 Files in this Repository
- `spam_detector.ipynb` → Jupyter/Colab notebook  
- `spam.csv` → Dataset file  
- `requirements.txt` → Project dependencies  
- `README.md` → Project details  

---

## 📊 Visualizations
- **Message Distribution**: Shows how many spam vs ham messages are in the dataset.  
- **Confusion Matrix Heatmap**: Shows model performance visually.  

---


