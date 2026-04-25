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
# Results

The models were evaluated using standard metrics. The Random Forest model performed best with high accuracy and ROC-AUC score.

# Future Improvements

* Improve model accuracy with more data
* Add more disease predictions
* Deploy the project online

---

# Author

Nithya Jakkampudi
