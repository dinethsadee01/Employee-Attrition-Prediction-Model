# Employee Attrition Prediction Mini-Game  

## Overview  
This mini-game is designed to predict employee attrition using machine learning techniques. It uses the **XGBoostClassifier** algorithm, optimized with **Hyperopt**, on a dataset containing over 74,000 records. The project demonstrates key AI concepts like feature engineering, hyperparameter tuning, and performance evaluation.  

## Features  
- Predicts whether an employee will leave or stay in a company.  
- Utilizes **RobustScaler** for scaling and **83-17 train-test split** for better model generalization.  
- Employs advanced hyperparameter tuning for optimal performance.  
- Includes feature encoding and detailed exploratory data analysis.  

## Technologies Used  
- **Python**  
- **Jupyter Notebook**  
- **XGBoost**  
- **Hyperopt**  
- **Pandas, NumPy, Matplotlib, Seaborn**  

## Dataset  
The dataset contains 74,498 records and 24 features, sourced from Kaggle, covering demographic, job-related, and personal data.  

## How to Run  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/dinethsadee01/Employee-Attrition-Prediction-Model.git  
   cd employee-attrition-prediction  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Open the Jupyter Notebook:  
   ```bash  
   jupyter notebook  
   ```  
4. Run the notebook file to train and evaluate the model.  

## Results  
The XGBoost model achieved high accuracy and interpretability. The hyperparameters optimized with Hyperopt yielded consistent improvements in performance metrics.  

## License  
This project is licensed under the [Apache 2.0](LICENSE) License. 
