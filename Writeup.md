# Diabetes Risk Forecast
Hernan Trujillo

#### Abstract
The objective of this project is to build a model that can identify potential diabetic patients based on the similar characteristics to other patients with diabetes diagnostic. About one in ten U.S. adults has diabetes now, according to the Centers for Disease Control and Prevention (CDC). But by 2050, that rate could skyrocket to as many as one in three. With this in mind, we will show how implementing Data Science we can support the Healtcare Systems such as Hospitals and Clinics identify potential Diabetic patients that show characteristics that are similar to other patients with the same diagnosis in order to provide early proffessional advise with medicine and treatments that can help patients take actions to control the process of becoming diabetic in the future. 

#### Design
My initial dataset from Kaggle 9 (originally from CDC) includes 2000 observations and 9 features that will will be expanded to begin the exploratory data analysis. Several constraints were placed on the selection of these instances from a larger database. In particular, since "Pregnancy" feature is included, we will assume that all patients here are females. Another important thing to consider is that the minimum age of the patients included on this dataset is 21 years old for legal purposes.

#### Data
The dataset contains 2,000 female patients at least of 21 years old. In order to avoid ethical contraints, all our patients had agreed with sharing their infomation and usage of their data for reserach purposes. Features included are initially 9 (all numerical) so we will be building aggregated features to meet the minimun of the 10 requested. A few feature highlights include measurements of pregnancy, age, blood pressure and insuline levels among others. 
I'm planning to apply some Feature Engineering to subset some of this features in order to evaluate levels of impact in my main Targey (Outcome: Diabetes).
- https://gis.cdc.gov/grasp/diabetes/DiabetesAtlas.html#¶
- https://www.kaggle.com/vikasukani/diabetes-data-set

#### Algorithms
Feature Engineering

Some preliminar EDA was done by using Excel. This preliminar work includes subsegmenting some features by level with conditional formulas.  
Then, I expanded my exploratory analysis bu using Python  which wasn't requested for this project but was successfully applied to understand better our dataset as well as building a baseline Classification Model with a high cv score of 95%. Feature engineering techniques were applied such as converting categorical features (Obesity, Overweight, BMI, etc) to binary dummy variables
Combining particular dummies and ranges of numeric features (Binaries) to highlight relationship among features.

#### Models (additional work)

Logistic regression and k-nearest neighbors classifiers were used before settling on Decision Tree Classifier as the model with strongest cross-validation performance. 

#### Tools
- Numpy and Pandas for data manipulation
- Scikit-learn for modeling
- Matplotlib and Seaborn for plotting
- Tableau for interactive visualizations https://public.tableau.com/app/profile/hernan.trujillo
- Excel for preliminar EDA process

#### Communication
In addition to the slides and visuals presented, Diabetes Risk Forecast will be embedded on my personal GitHub blog.

#### Impact Hypothesis:
The impact for the business on Healthcare System (Hospitals and Clinics) would include the following:

- [PRESENT SERVICES] + [NEW MARKETS] Develop new markets or market segments:
There is opportunity for new/additional business when it is possible to expand the number of patients. We can identify where and how current services answer a need for a new group of prospective patients.

- [NEW SERVICES] + [EXISTING MARKETS] Develop new products or services:
The core idea is to bring new, different or better exams or tests to current patients. Product development is based on a clear understanding of the needs and interests of the patients base and being able to offer a treatment that is responsive to those needs such an early detection.

#### Summary

The results showed that Decision Tree Classifier was the model with the higest score for our Classification Model. It was based on the variables/datasets analyzed as well as a cross validation process was made. It plotted each feature against my Target (Outcome) to verify the correlations among them so I can finally conclude that some of the most important features to be included in my model are Age, BMI (weight) and Blood Pressure. Surplirsely, Pregnancy didn't impact the results to much so we can assume that pregnancy in general, as well as the number of them, won't be part of our health care preventive reccomendations of being Diabetic. 
