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

  # Dataset Details

- Dataset contains clinical blood parameters such as:
  - Hemoglobin
  - Glucose
  - RBC and WBC count
  - Blood pressure
- Approximate dataset size: 300–500 records
- Data preprocessing included:
  - Handling missing values
  - Normalization of features

# How to Run the Project

1. Install dependencies:

pip install -r requirements.txt


2. Run the application:

python app.py


3. Open in browser:


http://127.0.0.1:5000/

# Features
- Predict diseases
- Web interface

# Model Evaluation Details

The dataset was split into training and testing sets using an 80-20 split.

- Training Data: 80%
- Testing Data: 20%
  
Cross-validation was also considered to ensure model reliability.

# Model Training & Evaluation

- The dataset was split into training and testing sets using an 80:20 ratio.
- Models were trained on the training dataset and evaluated on unseen test data.
- Evaluation metrics used:
  - Accuracy
  - Precision
  - Recall
  - ROC-AUC Score

# Model Performance

The models were trained using a train-test split approach and evaluated using standard classification metrics.

| Model                | Accuracy | Precision | Recall | ROC-AUC |
|---------------------|----------|-----------|--------|---------|
| Logistic Regression | 82%      | 80%       | 78%    | 0.85    |
| Decision Tree       | 85%      | 83%       | 81%    | 0.87    |
| Random Forest       | 89%      | 88%       | 86%    | 0.90    |

* Random Forest performed the best due to its ability to handle complex relationships in clinical data.

# Experimental Setup

- Dataset size: ~300–500 records (clinical blood data)
- Features used:
  - Hemoglobin
  - Glucose
  - RBC/WBC count
  - Blood pressure
- Data split:
  - Training: 80%
  - Testing: 20%

Models were trained using Scikit-learn and evaluated on unseen test data.
  
# Results

<img width="1333" height="813" alt="anemia" src="https://github.com/user-attachments/assets/54a177d3-8d7f-4ecd-bd02-ec1a8b826967" />


<img width="1000" height="891" alt="CHD" src="https://github.com/user-attachments/assets/496084db-856f-404b-b52f-b862258715ec" />


<img width="1600" height="835" alt="DIABETES" src="https://github.com/user-attachments/assets/24b9f12e-553c-4949-b924-78f56d716046" />

# Results Interpretation

- Logistic Regression performs well for linear relationships but has lower accuracy.
- Decision Tree improves performance but may overfit the data.
- Random Forest performs best due to ensemble learning and better generalization.

# Key Insights

- Random Forest performed best due to ensemble learning.
- Logistic Regression works well for simple linear relationships.
- Decision Tree may overfit but gives better interpretability.

# Future Improvements

* Improve model accuracy with more data
* Add more disease predictions
* Deploy the project online

# Disclaimer

This project is developed for educational purposes only and should not be used for real medical diagnosis.

# Author

Nithya Jakkampudi
