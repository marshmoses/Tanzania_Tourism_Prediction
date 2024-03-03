<<<<<<< HEAD





=======
# Tanzania_Tourism_Prediction:

Tourist Expenditure Prediction Model:

INTRODUCTION:

This project aims to develop a machine learning model that can predict the range of expenditures
a tourist might incur while visiting Tanzania. The model is intended to assist tour operators and
the Tanzania Tourism Board in estimating the expenditure of tourists from different countries,
age groups, travel companions, and other relevant factors. 
By providing an accurate expenditure estimate, this model can help tourists plan their trips 
effectively and enable tourism stakeholders to offer tailored services.

DATASET:

The dataset used for this project consists of two CSV files: Train.csv and Test.csv.
Each row in these files represents a different tour, with various attributes
such as the tourist's country of origin, age group, travel companions,
purpose of the trip, main activity, information source, tour arrangement, and more.
Additionally, the dataset includes the total cost of the tour, which serves as the target variable for our prediction model.
The data was derived from from a hackathon from Zindi platform.

PRELIMINARY PREPROCESSING:

The data we have we do have some columns with missing data.
the missing data ,we shall address it in relation to relevance with our target variable and the amount of missing data.

EDA

we explore the relation of numerical data using kDE.
For categorical data we shall first encode the data and tthen plot scatteer plots against our target variable.

DATA PREPARATION

We shall introduce one hot encoding using low cardinality .
our columns will increase following this

FEATURE ENGINEERING

some of our data is in object form.we need to convert it to float.
this will be possible by label encoding,and conversion of some columns using median to new numerical columns


MODEL SELECTION

i have explored tree based model and regression models
using cross-validation.
decision tree seems overfitted.
random forest performs best.


MODEL TUNING

after tuning with adjusting parameters until we get best results.
Random forest outperforms all with 38.2 points