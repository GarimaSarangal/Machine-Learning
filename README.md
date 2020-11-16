# Non Fraudulent Job Recommender
Our system filters out the fraudulent job postings before recommending the jobs based on the details provided by the user.

Note- Both the jupyter notebooks uploaded to GitHub contains the corresponding output with it.

# Phase one - EDA and Fraudulent job Classifier
Kindly execute using https://colab.research.google.com/ and upload the necessary files as mentioned in the Input Data Files Section.

Code file - Phase_One_EDA.ipynb <br>
Input data files - fake_job_postings.csv <br>
Output - Preprocessed_data.csv <br>
Description of code file - We performed EDA on our original dataset (fake_job_postings.csv) and the hypothesis mentioned in phase one of the Report are experimented. Also, we performed pre-processing on dataset. The output of this notebook is a dataset (Preprocessed_data.csv) <br>


# Creating a Job Recommender
Kindly execute using https://colab.research.google.com/ and upload the necessary files as mentioned in the Input Data Files Section.
Code file - Filter_and_Recommender.ipynb<br>
Input data files -

* fake_job_postings.csv
* Preprocessed_data.csv
* User_Resume.docx

Output - Recommended_jobs.csv<br>
Description of code file - We have evaluated different ML models - Logistic Regression, K-Nearest Neighbors, Support Vector Classifier, Random Forest Classifier and Decision Tree Classifier using AUC-ROC score. Created fruadulent job filter using Decision Tree Classifier. Also, we preprocessed user resume and developed recommender system using cosine similarity.
