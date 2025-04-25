# Employee loan Prediction

Objective: Predict employees' loan eligibility based on profile data such as income, credit score, and employment history.

# • Data Preparation & Preprocessing:
Cleaned and preprocessed raw data, handling missing values, encoding categorical features, and normalizing numerical fields.

Performed feature selection to retain the most relevant attributes for model performance.

# • Imbalanced Data Handling:
Detected class imbalance in the target variable (eligible vs ineligible).

Applied SMOTE (Synthetic Minority Oversampling Technique) and undersampling methods to balance the dataset.

# • Model Comparison:
Trained and compared multiple ML algorithms:
Logistic Regression, Random Forest, XGBoost, KNN, and SVM.

Evaluated using metrics: Accuracy, Precision, Recall, F1-Score, and AUC-ROC.

# • Hyperparameter Tuning:
Applied GridSearchCV and RandomizedSearchCV for fine-tuning model parameters.

Used 5-fold cross-validation to ensure generalization and reduce overfitting.

# • Performance Boost:
After applying imbalance correction and hyperparameter tuning, model performance improved by 10% in terms of F1-score and AUC.

✅ Final Outcome:
XGBoost delivered the best results and was selected as the final model for deployment.

# Git Clone....
git clone https://github.com/ 

git config --global user.name "abcuser" <Br>
git config --global user.email "abc@gmail.com" <br>

## Create Virtual Environments & activate:- 
python -m venv python_env <Br>
venv/Scripts/activate

### Emplyees Loan Amount Prediction Database:- [http://www.kagle.com/datasets/](https://www.kaggle.com/datasets?search=loan_data)

# Install dependencies
pip install -r requirements.txt


## Targets variables:-  loan_status 

## Independent Variables:-
person_age	person_gender	person_education	person_income	person_emp_exp	person_home_ownership	loan_amnt	loan_intent

brew install git-lfs              # or download from https://git-lfs.github.com/ <Br>
git lfs install <Br>
git lfs track "models/trained_model.pkl"  -- ".pkl" <br>
git add .gitattributes <br>
git add models/trained_model.pkl  <Br>
git commit -m "Add trained model with Git LFS" <br>
git push origin development <br>

git lfs push --all origin main <br>

