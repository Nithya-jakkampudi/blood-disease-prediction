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

# Model Performance

The models were evaluated using standard classification metrics:

| Model                | Accuracy | Precision | Recall | ROC-AUC |
|---------------------|----------|-----------|--------|---------|
| Logistic Regression | 82%      | 80%       | 78%    | 0.85    |
| Decision Tree       | 85%      | 83%       | 81%    | 0.87    |
| Random Forest       | 89%      | 88%       | 86%    | 0.90    |

* Random Forest performed the best among all models with the highest accuracy and ROC-AUC score.

# Results
<img width="1333" height="813" alt="anemia" src="https://github.com/user-attachments/assets/54a177d3-8d7f-4ecd-bd02-ec1a8b826967" />

<img width="1000" height="891" alt="CHD" src="https://github.com/user-attachments/assets/496084db-856f-404b-b52f-b862258715ec" />

<img width="1600" height="835" alt="DIABETES" src="https://github.com/user-attachments/assets/24b9f12e-553c-4949-b924-78f56d716046" />

# Future Improvements

* Improve model accuracy with more data
* Add more disease predictions
* Deploy the project online

# Author

Nithya Jakkampudi
