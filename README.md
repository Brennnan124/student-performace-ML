

# Student Exam Performance Prediction

## Overview

This project uses machine learning models to predict whether a student will pass or fail based on various personal, family, and academic attributes. The dataset used is the **Student Performance Data** from the UCI Machine Learning Repository.

## Dataset

The dataset contains student records with features like age, study time, failures, family support, and grades. It was used to train and test multiple classification models.

## Installation & Setup

1. Make sure you have Python installed.
2. Install the required Python libraries using:

   ```
   pip install -r requirements.txt
   ```

## Usage

To run the analysis, open the notebook:

```
jupyter notebook notebooks/ML CAT1.ipynb
```

and follow the cells sequentially.

## Project Structure

```
Student-performance-ML/
├── data/               # Dataset CSV files
├── notebooks/          # Jupyter notebook(s)
├── output/             # (if you generated any output files)
├── README.md           # This file
└── requirements.txt    # Python dependencies
```

## Results

Three models were tested:

* **Logistic Regression**
* **Decision Tree**
* **Random Forest**

### Model Performance:

| Model               | Accuracy | F1 Score |
| :------------------ | :------- | :------- |
| Logistic Regression | 0.8820   | 0.9341   |
| Decision Tree       | 0.8256   | 0.8976   |
| Random Forest       | 0.8820   | 0.9359   |

**Best model:** Logistic Regression

### Confusion Matrix (Logistic Regression)

|                 | Predicted Fail | Predicted Pass |
| :-------------- | :------------- | :------------- |
| **Actual Fail** | 45             | 8              |
| **Actual Pass** | 12             | 120            |

## Conclusion

The Logistic Regression model gave the best balance of accuracy and F1-score in predicting student exam performance. This project demonstrates the application of basic classification models in an educational data mining context.

---

