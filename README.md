# My Data Science Portfolio
List of all my data science projects

# [Project 1: Rice Field Predictor](https://github.com/dzelrahman/RiceFieldPredictor "Project Repo")
* The objective is to determine rice field proportion and location that covers particular region in Indonesia, which in this project is Banyuwangi
* Use object detection algorithm (Single Shot Multibox Detector) to achieve those objectives.
* Use ArcGIS pro to label each object into four classes that constitutes satellite raster imagery 
* Use ArcGIS pro to augment and pre-process the image data to make it compatible for model fitting and training. 
* Use python module named `arcgis.learn` which is included in ArcGIS pro built in python module to build SSD model algorithm.
* This project is already written in [essay form](https://medium.com/analytics-vidhya/rice-field-predictor-727b03eeffee) that is published in Analytics Vidhya's Medium page where I create a story that explains the working process and steps I took in building this project, starting from data collection until model evaluation.

# [Project 2: Covid-19 Analysis and Prediction](https://github.com/dzelrahman/Covid19AnalysisPrediction "Project Repo")
* This project is made when Covid-19 pandemic was still in early phase, thus the data is still limited and cannot be used as real guidelines.
* The objective is just to do simple data exploration and visualization using Covid-19 case data that had been published by John Hopkins University.
* Data visualization is generated to know the number of Case Fatality Rate and Recovery Rate through using GGPLOT, the well known R-package for creating compelling data visualization. 
* Prediction modeling is done by using FB Prophet machine learning algorithm to know the number of cases and death in the extend of next month, assuming that the growth rate has exponential nature. 
* This project is already written in [essay form](https://medium.com/@dzelrahman/analisa-dan-prediksi-covid-19-f706cac9786e) that is published in my personal Medium page where I create a story that explains the working process and steps I took in building this project, starting from data collection until model evaluation. I use my mother language here.

# [Project 3: Vaccine Receiver Predictor - On Going](https://github.com/dzelrahman/vaccine_receiver_predictor "Project Repo")
* The project is part of the challenge held by DrivenData called "Flu Shot Learning". The purpose of this challenge is to predict the probability of receiving vaccine from each of survey respondents based on the answer they gave to the medical authority.
* There are some statistic works and data cleaning process before feeding it into machine learning models, such as examining the collinearity of each variable and imputing the missing data using several method, such as logistic regression and median. 
* The preliminary model that is presented is using logistic regression, since the purpose is just to determine the most important variable toward the model. 
* There are several works to done such as creating the model to predict the probability of receiving vaccine and several other statistical examination in order to create the model as robust as possible.
* This project can be seen in nbviewer which I put the link [here](https://nbviewer.jupyter.org/github/dzelrahman/vaccine_receiver_predictor/blob/master/flu_shot_learning/new_attempt_data_exp.ipynb). The notebook is written in Bahasa Indonesia.
