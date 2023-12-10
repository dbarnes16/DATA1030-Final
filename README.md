# DATA1030-Final
DATA1030 Final Project Dominique Barnes. Created a pipeline for a machine learning model to predict physical activity class on new unseen users. The data was collected by the [WIreless Senor Data Mining Lab (WISDM)](https://www.cis.fordham.edu/wisdm/dataset.php) at Forham University in 2012. The goal of the final project was to develop a model classifier to identify six physical activity classes (downstairs, jogging, sitting, standing, walking, upstairs) through phone-based accelerometer readings. The dataset was source from [Kaggle]([https://www.kaggle.com/datasets/krishnamore/activitydetectionimusensor]). 

The project was built on Python 3.11.4 and repository organization as follows
1. data/ - Stores all raw and preprocessed data files from the WISDM Lab
2. figures/ - Stores ll visualizations including EDA and model result comparions
3. results/ - Trained models pickled files
4. report/ - Reports on development, pipeline, methodology, and model results. Presented in word document as final report and powerpoint presentation
5. src/ - All of the code for: data importing, EDA; group based splitting, preprocessing and model development; model evaluations, result visualizations and feature importances in IMU_Final_Project.ipynb

   
Key packages used in this project are the following:
'numpy': "1.24.4"
'matplotlib': "3.7.2"
'sklearn': "1.3.0"
'pandas': "2.0.3"
'xgboost': "1.7.6" 
'shap': "0.42.1"
'seaborn': "0.12.2"
