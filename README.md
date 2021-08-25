# Diabetes Predictor
About one in ten U.S. adults has diabetes now, according to the Centers for Disease Control and Prevention (CDC). But by 2050, that rate could skyrocket to as many as one in three. With this in mind, we will show how implementing Data Science we can support the Healtcare Systems such as Hospitals and Clinics identify potential Diabetic patients that show characteristics that are similar to other patients with the same diagnosis in order to provide early proffessional advise with medicine and treatments that can help patients take actions to control the process of becoming diabetic in the future.

### Question/Need:

##### What is the framing question of your analysis, or the purpose of the model/system you plan to build?

I am planning to build a model that can identify potential diabetic patients based on the similar characteristics to other patients with diabetes diagnostic.

##### Who benefits from exploring this question or building this model/system?

It's economically lucrative for Hospitals and Clinics as diabetes treatments  are often extremely expensive in the US and the per patient revenues could be very significant. Also, patients would be beneficted by the early detection of diabetes and avoind future complications.

That said, it becomes a great business opportunity for Hospitals and Clinics to have a model that can predict potential diabetes patterns among their patients as earliest as possible.

### Data Description:

My initial dataset from Kaggle 9 (originally from CDC) includes 2000 observations and 9 features that will will be expanded to begin the exploratory data analysis. Several constraints were placed on the selection of these instances from a larger database. In particular, since "Pregnancy" feature is included, we will assume that all patients here are females. Another important thing to consider is that the minimum age of the patients included on this dataset is 21 years old for legal purposes.

##### What dataset(s) do you plan to use, and how will you obtain the data?

Centers of Disease Control and Prevention CDC has public data on this matter https://gis.cdc.gov/grasp/diabetes/DiabetesAtlas.html#

Kaggle also has several datasets related to this topic. We will be using the following dataset from Kaggle (originally extracted from the main CDC dataset): https://www.kaggle.com/vikasukani/diabetes-data-set

##### What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?

Using a cohort of patients who have been confirmed to have diabetes, we can create a ML model that can then be applied to other patients to identify potential undiagnosed cases / patients by transforming features with specific parameters and ranges (Feature Engineering) to succesfully applied a Classification Model. 

##### If modeling, what will you predict as your target?

The objective of the dataset is to predict among non-diabetic patients whether or not a patient has diabetes or might potencially become in one (prediabetes), based on certain characteristics of positive patients.

##### What would be your impact / impact hypothesis:

The impact for the Healthcare System would include the following:

#### [PRESENT SERVICES] + [NEW MARKETS] Develop new markets or market segments:

There is opportunity for new/additional business when it is possible to expand the number of patients. We can identify where and how current services answer a need for a new group of prospective patients. 

#### [NEW SERVICES] + [EXISTING MARKETS] Develop new products or services:

The core idea is to bring new, different or better exams or tests to current patients. Product development is based on a clear understanding of the needs and interests of the patients base and being able to offer a treatment that is responsive to those needs such an early detection.

### Tools:

##### How do you intend to meet the tools requirement of the project?

I'm considering to use Pandas, Matploblib and Seaborn libraries in Python to the preliminar analysis. Also, Google Sheets and Tableu for visualization purposes.  

##### Are you planning in advance to need or use additional tools beyond those required?

I will apply ML techniques to build a Classification Model in Python.

### MVP Goal:

##### What would a minimum viable product (MVP) look like for this project?

Some plots that can initially show total diabetes diagnosis in out dataset. Also, Blood Pressure and BMI (weight) compare with the outcome will be part of the MVP request. 
