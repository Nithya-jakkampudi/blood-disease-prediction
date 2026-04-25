# Blood Disease Prediction System

# Overview

This project predicts blood-related diseases such as anemia, diabetes, and heart disease using machine learning algorithms. It takes clinical input parameters and provides predictions through a web interface built with Flask.

# Features

* Predict diseases based on blood test parameters
* User-friendly web interface using Flask
* Multiple machine learning models used for prediction

# Machine Learning Models

The following models were trained and evaluated:

* Logistic Regression
* Random Forest
* Decision Tree

Evaluation metrics used:

* Accuracy
* Precision
* Recall
* ROC-AUC Score

# Project Structure

* `app.py` → Main Flask application
* `templates/` → HTML files
* `static/` → CSS and JS files
* `pickle_models/` → Trained machine learning models
* `csv/` → Dataset files

# Technologies Used

* Python
* Flask
* Pandas
* NumPy
* Scikit-learn

# How to Run the Project

1. Install dependencies:

```
pip install -r requirements.txt
```

2. Run the application:

```
python app.py
```

3. Open in browser:

```
http://127.0.0.1:5000/
```
# Features
- Predict diseases
- Web interface

## 📸 Screenshots

<img width="1333" height="813" alt="anemia" src="https://github.com/user-attachments/assets/581896e4-e619-402f-b4d6-f204d932f71a" />

<img width="1000" height="891" alt="CHD" src="https://github.com/user-attachments/assets/8deb9df5-b2a1-4a7b-8f46-ba95d3221b8e" />

<img width="1600" height="835" alt="DIABETES" src="https://github.com/user-attachments/assets/f754454b-a7df-4c22-9aae-355461f8f0e0" />

# Results
- Logistic Regression Accuracy: 82%
- Random Forest Accuracy: 89%
- ROC-AUC Score: 0.90

# Future Improvements

* Improve model accuracy with more data
* Add more disease predictions
* Deploy the project online

# Author

Nithya Jakkampudi
