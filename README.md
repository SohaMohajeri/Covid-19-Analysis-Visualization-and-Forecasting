<div align="center">
  
# Covid-19 Analysis, Visualization and Forecasting
</div>


<div align="center">
<img src="https://user-images.githubusercontent.com/69224996/97096485-fbd98300-1621-11eb-8230-3f30c6d2f320.jpg" >
</div>

<br />


<div align="justify">

From World Health Organization - On 31 December 2019, WHO was alerted to several cases of pneumonia in Wuhan City, Hubei Province of China. The virus did not match any other known virus. This raised concern because when a virus is new, we do not know how it affects people. So daily level information on the affected people can give some interesting insights when it is made available to the broader data science community. Johns Hopkins University has made an excellent dashboard using the affected cases data, and our data is extracted from this dashboard.

In this notebook we will use Covid-19_Datase that is the same as COVID19_line_list_data.csv dataset taken from https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset, but the only difference is that in our dataset death and recovered features are encoded as (0 or 1) and not in form of dates as in the former dataset.

There are three parts to our report, as follows:

- Data Cleaning and Feature Engineering
- Exploratory Data Analysis
- Prediction of Death or Recovery of Patients

Our first objective is to find out the factors that are more important in the death and recovery of patients. Our second purpose is to implement several machine learning algorithms such as Logistic Regression, Decision Tree Classifier, Random Forest Classifier, Support Vector Classifier and XGBoost Classifier to predict the death and recovery of patients and compare the result to discover which algorithm works better for this specific dataset.

</div>

