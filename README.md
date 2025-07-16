
# 🩺 Personalized Health Care System using Machine Learning

This project is a **Personalized Health Care Web Application** built with **Flask (Python)** for the backend and **HTML/CSS/JavaScript** for the frontend. It utilizes **Machine Learning** to predict diseases based on user-inputted symptoms and provides relevant health recommendations including medications, precautions, diet, and workout tips.

---

## 🚀 Features

- 🔍 **Symptom-Based Disease Prediction**  
  Enter symptoms (comma-separated) and get instant disease predictions using an ML model.

- 💊 **Personalized Health Recommendations**  
  - Disease Description  
  - Precautionary Measures  
  - Suggested Medications  
  - Dietary Tips  
  - Workout Routines

- 🧠 **Machine Learning Integration**  
  A trained ML model predicts diseases based on user symptoms.

- 💻 **Interactive UI**  
  Responsive and user-friendly interface with autocomplete symptom suggestions.

---

## 🛠️ Tech Stack

| Component       | Technology           |
|----------------|----------------------|
| Backend         | Flask (Python)       |
| Frontend        | HTML, CSS, JavaScript |
| Machine Learning| scikit-learn, pandas |
| Deployment      | Flask App Server     |

---

## 🧬 How It Works

1. User enters symptoms in a form (comma-separated).
2. The symptoms are passed to the backend using a POST request.
3. The ML model predicts the most probable disease.
4. The app returns:
   - Disease name
   - Description
   - Precautions
   - Medications
   - Diet and workout suggestions
  
