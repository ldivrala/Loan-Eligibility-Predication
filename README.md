# Loan Eligibility predication
Dataset :: [Loan Prediction Problem Dataset](https://www.kaggle.com/altruistdelhite04/loan-prediction-problem-dataset "Loan Prediction Problem Dataset")

* Dataset :: data contains diffrent attributes like gender, married, education, income, self employed, loan amount etc.

* Inspiration::
  * Our aim was to try to analyze the dataset corelations and try to figure out what factors are important for loan approval.
  * Is candidate is eligible for loan?
  
  
- Steps (What we did) :: 
  - Reduce memory usage, Checking Data information (With Pandas).
  - EDA :: 
    1. Pair plot WRT Loan_Status.
    2. Divide columns on the basis of Category, Continous Values.
    3. Count plot for Category values WRT Loan_Status Columns (To analysis of category values for approval). 
    4. Histogram Plot for Continous values WRT Price Columns (To analysis of continous values for approval).
    4. Handle missing Values.
    5. Corelation WRT diffrent columns.

  - Prediction ::
    1. Handle Categorical Values (OneHot encoding).
    3. Standardisation (Preprocessing of Data)
    4. Prediction by Logictic Regression(0.79), SVM(0.78), Neural Network (Tensorflow, Keras)(0.78)
    5. Accuracy :: 0.78 (Approx)
 


