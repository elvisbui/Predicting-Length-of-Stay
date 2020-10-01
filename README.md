# Introduction
In this project, I will outline how I will go about doing a machine learning project. 
I will be using this dataset for this project: https://www.kaggle.com/nehaprabhavalkar/av-healthcare-analytics-ii

# Pipeline
1. Understanding the Problem
2. Exploratory Data Analysis (EDA)
3. Data Formatting and Cleaning
4. Baseline Model Building
5. Review Model Score
  * Review Validation Schema
  * Improve Validcation Strategy
6. Error Analysis
7. Deeper Exploratory Data Analysis
8. Research
9. Improving Model
  * Feature Engineering
  * Feature Selecting
  * Data Augmentation 
  * Target Engineering
  * Architecture Tuning
10. Experimentation
11. Build and Run New Model
12. Repeat steps 4-10
13. Ensemble

# 1. Understanding the Problem
In this project, I will be predict the amount of time a patient with stay at a given hospital.
 
# 2. Exploratory Data Analysis (EDA)
In my basic exploratory data analysis, for each feature I will see what type of data it is, if there are any missing values, if there are any outliers, and if the values of the features need to be preprocessed. The main goal of EDA for me is to gain insight. In this stage, I will also be determine which model is best for the baseline model. 
 
# 3. Data Formatting and Cleaning 
After look at the data, I will fill in missing data, remove outliers, and preprocess the data for the baseline model.

# 4. Baseline Model Building
The goal of the baseline model is to have a standard to work from and compare to. It is a simple model with a simple pipeline. There will be no fancy validation scheme or complex optimization for the baseline model. I will start simple, debug the model and pipeline, and slowly grow the complexity of the pipeline. This methodical way of building a machine learning project will make debugging and testing a lot easier. 

# 5. Review Model Score
The next step is to review the baseline model and list out things that would be improved. I will also be refining the validation schema. 

# 6. Error Analysis
In this stage, I will check how the model is fitting the data and figure out ways to improve the model. 
 
# 7. Deeper Exploratory Data Analysis
I like to look at the data a lot when I'm improving my model, to see if I could be better insight on how to improve my models. 
In this step, I will review my data and try to get a better understanding of the data.
 
# 8. Research
When I'm done reviewing my data and model, I will research online of similiar problems other people have faced or try to find research papers on the data or model I'm using. 
 
# 9. Improving Model
After resreaching, it is time to improve my model performance. For feature engineering, I like to create as many features as I can and I will not remove features in this stage. This is because I might create a new feature that works well if another unimportant feature. 

When I'm done creating all my features, it is time to select the best features. I will run the model multiple times, testing a subset of features each time, and removing features that improves the model when it is omitted. Each model has different features that work well with the model. So I will have to run feature selection for each model independently. 

Once I found all the important features, I will then start tuning the architecture of the models and optimize the hyperparameter. 

# 10. Experimentation
I found out that experiementation and iteration are important in improving a model's performance. In this stage, I will list all the ideas I can try to improve the model. 

# 11. Build and Run New Model
Now I will create a lot of new models to test the new architecture, and run a lot of experiments to see which models are the best. 

# 12. Repeat steps 5-11
After creating a lot of new models, I will have to review the models score, analysis the error, look deeper into the data, research, improve the model, and experiment with new ideas again. Creating a well preforming machine learning project requires a lot of iterations, testing, debuging, and experimentation. 

# 13. Ensemble
After I am satisfied with my models and their preformance, I will then start the ensemble stage. Ensemble learning is costly, but it can yield great preformance increases.
 
 
 # Reference
[Beyond Feature Engineering and HPO | by Jean-François Puget | Kaggle Days Paris](https://www.youtube.com/watch?v=VC8Jc9_lNoY)
