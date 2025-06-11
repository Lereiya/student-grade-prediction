#  Student Grade Prediction

This project uses machine learning to predict whether a student will pass or fail based on personal and academic attributes.

## Files
- `student-performance.csv`: The dataset
- `student_pass_prediction.ipynb`: Jupyter Notebook with full ML pipeline
- `README.md`: Project overview

##  Objective
To train classification models (Logistic Regression and Random Forest) to predict student pass/fail based on input features.

##  Models Used
- Logistic Regression
- Random Forest Classifier

##  Results
| Model              | Accuracy | F1 Score |
|-------------------|----------|----------|
| Logistic Regression | 76%    | 0.74     |
| Random Forest       | 88%    | 0.87     |

**Best Model:** Random Forest Classifier

##  How to Run
1. Clone this repo
2. Open `student_pass_prediction.ipynb` in Jupyter Notebook
3. Run all cells top to bottom

##  Requirements
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib
