# Credit-Card-Fraud-Detection
This project is focused on building a machine learning model for Credit Card Fraud Detection. The main objective is to identify fraudulent transactions accurately while minimizing false positives. The dataset provided includes two files: fraudTrain.csv and fraudTest.csv, containing transaction information such as amount, merchant details, user ID, timestamps, and more. The workflow starts by loading the data, cleaning it by handling missing values, and preparing features by encoding categorical variables. A Random Forest Classifier is used to build the model because of its robustness and good performance in classification tasks. After training, the model's performance is evaluated using metrics like precision, recall, F1-score, and confusion matrix analysis. Special focus is given to understanding misclassifications (false positives and false negatives) to further improve the model in the future. Libraries such as pandas, numpy, scikit-learn, matplotlib, and seaborn are utilized in this project. In the future, improvements like trying advanced models (XGBoost, LightGBM), feature selection, hyperparameter tuning, and building a real-time fraud detection dashboard can be considered. This project is developed as part of academic learning and practical machine learning implementation.


#This is the overall idea of the Project

Credit-Card-Fraud-Detection/
│
├── fraud det.ipynb
├── fraudTrain.csv
├── fraudTest.csv
├── README.md
