# Personality-prediction-and-resume-analysis
Personality is predicted using Multinomial Logistic Regression which is a machine learning algorithm and the features from the resume are extracted.
# Personality Prediction System

 It features two user roles:

- **Candidate**: Submits personal details and uploads a resume for personality prediction.
- **Admin**: Logs in to view all predictions and candidate details in a secure dashboard.

---

## 🎯 Features

✅ Predict personality traits using a trained machine learning model  
✅ Extract skills and information from resumes (PDF or DOCX)  
✅ Admin-only dashboard to view candidate data and predictions  
✅ Simple and clean Tkinter-based user interface  
✅ Stores submission data in a CSV file for persistent storage  

---

## 🧠 How It Works

- Candidate fills in:
  - Name, gender, age
  - Big Five personality traits (1-10 scale)
  - Uploads resume (PDF or DOCX)
- Resume text is extracted using NLP (spaCy)
- Logistic Regression model predicts the candidate's personality type
- Submissions are stored in `submissions.csv`
- Only admin users can view all submissions and predictions

---

## 🛠️ Tech Stack

- Python 3
- scikit-learn
- pandas
- numpy
- spaCy NLP
- PyPDF2
- python-docx
- Tkinter GUI
