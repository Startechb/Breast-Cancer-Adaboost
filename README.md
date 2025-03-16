# Breast-Cancer-Adaboost
Machine learning model for breast cancer detection using AdaBoost and Bagging.
#  Breast Cancer Classification using AdaBoost  

##  Project Overview  
This project implements the **AdaBoost algorithm from scratch** and compares it to other ensemble methods like Bagging and Decision Trees to classify breast cancer tumors as **Malignant or Benign**.  

##  Dataset  
- **Dataset Used:** Breast Cancer Wisconsin Dataset  
- **Features:** 10 selected features  
- **Target Variable:** 0 (Malignant) or 1 (Benign)  

##  Implementation Steps  
1️. **Data Preprocessing**  
   - Load the dataset  
   - Perform feature selection  
   - Split data into training and testing sets  

2️. **Model Training & Comparison**  
   - Train a **Decision Tree Classifier**  
   - Train an **AdaBoost Classifier** using Decision Stumps  
   - Train a **Bagging Classifier**  

3️. **Evaluation & Results**  
   - Compare accuracy of different models  
   - Visualize decision boundaries  

##  Results  
- **Single Decision Tree Accuracy:** 92.98%  
- **Bagging Classifier Accuracy:** 93.49%  
- **AdaBoost Accuracy:** 96.49%  

### Takeaways  
✅ AdaBoost outperformed Decision Trees and Bagging.  
✅ Ensemble methods help improve accuracy and reduce overfitting.  
✅ Further tuning or feature engineering could improve performance even more.  

 ## Installation & Running the Code  
To run this project, install dependencies using:  

```bash
pip install -r requirements.txt
