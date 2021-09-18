### Prediction of Placement Result

#### Overview 

In this project, we'll look at the placements record and try to build a classifier to predict whether a given profile likely to be get placed or not.

#### Data used

Placement_Data_Full_Class.csv - Download from kaggle datasets (https://www.kaggle.com/sevdanurgenc/placement-data-full-class)

#### Data Description

##### Shape - (215, 15)

##### Data columns (total 15 columns):
sl_no - int64<br>
gender -  object<br>
ssc_p - float64<br>
ssc_b - object<br>
hsc_p - float64<br>
hsc_b - object<br>
hsc_s - object<br>
degree_p - float64<br>
degree_t - object<br>
workex - object<br>
etest_p - float64<br>
specialisation - object<br>
mba_p - float64<br>
status - object<br>
salary -float64<br>

#### Folders

* /app/ - Python files for the deployment of the trained machine learning model as an API using FastAPI( )
* /model/ - Jupyter Notebook for training the model and the trained model in pickle format
* /Data/ - Data used for training the model in csv format
