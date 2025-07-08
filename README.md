# 📄 Resume Category Predictor using NLP & Streamlit

This is a web-based application that classifies resumes into job categories using Natural Language Processing (NLP) techniques. Built with Streamlit, it allows uploading resumes in PDF, DOCX, or TXT format and uses a trained SVM model with TF-IDF features for classification. The app also extracts insights like skills, education, certifications, and experience.

UI demo video: https://www.linkedin.com/posts/rajdeep-mohanty-1783731ba_nlp-resumeparser-machinelearning-activity-7347001056138055680-Nx5N?utm_source=share&utm_medium=member_desktop&rcm=ACoAADL0kCwB99OuGbP9kHdaAyoPt1V_7pKCJv8

---

## 🚀 Features
- Upload resumes in **PDF, DOCX, or TXT**
- Clean text using regex-based preprocessing
- Predict resume category using **SVM + TF-IDF**
- Extract useful information: **Skills**, **Education**, **Certifications**, **Experience**
- Simple and clean **Streamlit UI**

---

## 🗂️ Project Structure
├── app/ # Python source code (e.g., app.py)
├── clf.pkl # Trained classification model (SVM)
├── clf.zip # Compressed model file (backup)
├── encoder.pkl # LabelEncoder used for category decoding
├── tfidf.pkl # Trained TF-IDF vectorizer
├── requirements.txt # List of required Python packages
├── Resume Screening with Python # Jupyter Notebook (EDA/training code)
├── UpdatedResumeDataSet.xlsx # Resume dataset used for training

Install required packages:

bash
pip install -r requirements.txt

▶️ Run the App
bash
Copy
Edit
streamlit run app/app.py
