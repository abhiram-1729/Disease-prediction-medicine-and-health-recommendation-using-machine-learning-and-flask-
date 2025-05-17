# Disease-prediction-medicine-and-health-recommendation-using-machine-learning-and-flask-
An intelligent web-based system that predicts diseases and recommends medications, diet, and workouts using machine learning and Flask.
# Disease Prediction and Medicine Recommendation System using Machine Learning and Flask

## 🌐 Project Overview

This project is a web-based healthcare assistant that leverages machine learning to **predict diseases** from user-input symptoms and provide **personalized recommendations** including:
- Disease Description with Confidence level
-  Medications
- Precautions
- Diet plans
- Workout suggestions


It is designed to support users who may lack immediate access to medical professionals, offering **first-level guidance** using a trained **Support Vector Classifier (SVC)** model.

---

## ⚙️ Tech Stack

- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** Python, Flask
- **Machine Learning:** SVC (Support Vector Classifier from scikit-learn)
- **Data Handling:** Pandas, NumPy
- **Visualization & Deployment:** Flask Web Interface

---

## 📌 Features

- User-friendly web interface to enter symptoms
- ML-based multi-disease prediction using SVC
- Displays:
  - Predicted disease
  - Recommended medications
  - Diet and workout plans
  - Precautionary measures
- Clean, readable UI for any user (no login needed)

---

## 🧠 Machine Learning Model (SVC)

Support Vector Classification (SVC) is a supervised learning algorithm used for classification tasks. It works by:
- Creating hyperplanes to separate disease classes
- Performing well with high-dimensional data
- Handling multi-class classification through one-vs-rest strategy

> SVC helps in predicting diseases where multiple symptoms overlap by finding optimal decision boundaries.

---

## 🔁 Workflow

1. User submits symptoms via the web form
2. Input is cleaned and encoded
3. Symptoms are passed to the trained SVC model
4. The predicted disease is fetched
5. Recommendations (medications, precautions, diet, workout) are retrieved and displayed

---

## ⚠️ Challenges Faced

- Handling overlapping symptoms across multiple diseases
- Dealing with unstructured or noisy input data
- Feature selection and encoding for categorical data
- Mapping human-readable symptom input to model-usable vectors
- Maintaining performance and accuracy in real-time prediction
- Integrating Flask backend seamlessly with ML logic

---

## 🔍 Comparison with Existing Methods

| Feature                  | Existing Systems           | This Project                           |
|--------------------------|----------------------------|----------------------------------------|
| Prediction Method        | Rule-based/static          | Dynamic ML-based (SVC)                 |
| Personalization          | Low                        | High                                   |
| Speed                    | Manual consultation needed | Instant response                       |
| Recommendations Offered | Few                        | Medicine, diet, workout, precautions   |
| Accessibility            | Limited                    | Accessible via any browser             |

---

## 📈 Scope of the Project

This system serves as a **first-level diagnostic and recommendation tool**, helping users:
- Quickly identify possible illnesses
- Understand basic precautionary and recovery measures
- Get guidance without waiting for appointments

> Future enhancements may include:
> - Real-time chatbot support
> - Multilingual interface
> - User health history tracking
> - Secure login/authentication system

---

## ✅ Conclusion

This project bridges healthcare and technology by using **machine learning** to deliver meaningful health insights instantly. While not a replacement for professional diagnosis, it serves as an **effective preliminary tool** to guide users toward better health awareness.

---

## 📚 References

- scikit-learn SVC Documentation: https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html
- Pandas Library: https://pandas.pydata.org/
- Flask Web Framework: https://flask.palletsprojects.com/
- Sample Disease Datasets (Kaggle): https://www.kaggle.com/

---

 ## Project Related Images
`Home Page`

![image](https://github.com/abhiram-1729/Ecommerce-website-using-Django-and-Javascript/blob/main/vedios/Homepage.png)

'Diagnosis'
![image](https://github.com/abhiram-1729/Ecommerce-website-using-Django-and-Javascript/blob/main/vedios/Homepage.png)

'Disease Description'
![image](https://github.com/abhiram-1729/Ecommerce-website-using-Django-and-Javascript/blob/main/vedios/Homepage.png)

'Precautions'
![image](https://github.com/abhiram-1729/Ecommerce-website-using-Django-and-Javascript/blob/main/vedios/Homepage.png)

'Workouts'
![image](https://github.com/abhiram-1729/Ecommerce-website-using-Django-and-Javascript/blob/main/vedios/Homepage.png)

'Diets'
![image](https://github.com/abhiram-1729/Ecommerce-website-using-Django-and-Javascript/blob/main/vedios/Homepage.png)






