
# Customer Churn Prediction

This repository contains a machine learning project aimed at predicting customer churn for businesses. Customer churn is when customers stop doing business with a company. By predicting which customers are likely to churn, companies can take preventive actions to retain them, thereby reducing losses and increasing customer satisfaction.




## Project Overview
   This project includes:

    1. Data preprocessing and cleaning.
    2. Exploratory Data Analysis (EDA) to understand the customer patterns.
    3. Feature engineering to create meaningful features for the model.
    4. Implementation of several machine learning models to predict churn.
    5. Evaluation of model performance and selection of the best model for deployment.
## Data Preprocessing

Data preprocessing steps include:

      1. Handling missing values by imputation or removal.
      2. Encoding categorical variables to make them usable by machine learning models.
      3. Scaling numerical features to normalize the data.
      4. Splitting the data into training and testing sets to evaluate the models.
## Evaluation 

Model performance was evaluated using various metrics:

      1. Accuracy
      2. Precision
      3. Recall
      4. F1-score
Additionally, we used a confusion matrix to analyze the classification results.
## Installation

To run this project locally, follow these steps:

1. Clone the repository:

```bash
  git clone https://github.com/yourusername/customer-churn-prediction.git
```
2. Navigate to the project directory:

```bash
  cd customer-churn-prediction
```

    
## Usage

After installation, you can start training the model and testing its performance. Run the following command to execute the main script:

```bash
  python main.py
```


## Results

Our best-performing model achieved an accuracy of 97% and an F1-score of 0.91 on the test dataset. The model can effectively predict customer churn and identify high-risk customers, allowing businesses to take preventive actions.
## Future Work

Future improvements to this project could include:

     1. Implementing deep learning models for better accuracy.
     2. Adding feature selection techniques to optimize the model further.
     3. Testing with a more extensive dataset for broader applicability.
     4. Developing a web interface for easy access to predictions.