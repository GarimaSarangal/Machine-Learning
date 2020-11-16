# Machine-Learning
Non Fraudulent Job Recommender
Our system filters out the fraudulent job postings before recommending the jobs based on the details provided by the user.

Note- Both the jupyter notebooks uploaded to GitHub contains the corresponding output with it.

Phase one - EDA
Kindly execute using https://colab.research.google.com/ and upload the necessary files as mentioned in the Input Data Files Section.

Code file - Phase_One_EDA.ipynb
Input data files - fake_job_postings.csv
Note - As our input files were greater than 25 mb, we were not able to upload to Github. Thus, refer the input files uploaded to Google Drive - Use NCSU credentials
Output - Preprocessed_data.csv
Description of code file - We performed EDA on our original dataset (fake_job_postings.csv) and the hypothesis mentioned in phase one of the Report are experimented. Also, we performed pre-processing on dataset. The output of this notebook is a dataset (Preprocessed_data.csv)

Creating a filter and job recommender
Kindly execute using https://colab.research.google.com/ and upload the necessary files as mentioned in the Input Data Files Section.
Code file - Filter_and_Recommender.ipynb
Input data files -

fake_job_postings.csv
Preprocessed_data.csv
User_Resume.docx
Note - As our input files were greater than 25 mb, we were not able to upload to Github. Thus, refer the input files uploaded to Google Drive - Use NCSU credentials
Output - Recommended_jobs.csv
Description of code file - We have evaluated different ML models - Logistic Regression, K-Nearest Neighbors, Support Vector Classifier, Random Forest Classifier and Decision Tree Classifier using AUC-ROC score. Created fruadulent job filter using Decision Tree Classifier. Also, we preprocessed user resume and developed recommender system using cosine similarity.
