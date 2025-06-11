Student Exam Performance Prediction

Overview
Predicts student pass/fail status using Machine learning. Dataset: [Student Performance Data]

Installation
1. Clone repository:
   bash
   git clone https://github.com/your-username/your-repo-name.git
   
2. Install dependencies:
   bash
   pip install -r requirements.txt
   
Usage
Run the main notebook:
  bash
jupyter notebook notebooks/ML CAT1.ipynb


Project Structure

student-performance-prediction/
data/          # Dataset
notebooks/     # Analysis notebook
README.md      # Current file 
requirements.txt 


Results

Best model: Logical regression
- Accuracy: 81%  
- F1-Score: 0.85  
Confusion Matrix:  
               Predicted Fail  Predicted Pass 

 Actual Fail  45        8        
 Actual Pass  12        120      

   Model              Accuracy  F1 Score 
 
 Logistic Regression  0.882051  0.934097 
 Decision Tree        0.825641  0.897590 
 Random Forest        0.882051  0.935933 

 Final Verdict:
The best performing model for this task was Logistic Regression, delivering an accuracy of 88.2% and an F1-Score of 0.93.



             Predicted Fail Predicted Pass 
Actual Fail  45              8             
Actual Pass  12              120            
