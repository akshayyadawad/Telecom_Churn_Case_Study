# Telecom_Churn_Case_Study

**Objectives**
The main goal of the case study is to build ML models to predict churn. The predictive model that you’re going to build will the following purposes:

- It will be used to predict whether a high-value customer will churn or not, in near future (i.e. churn phase). By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc.
- It will be used to identify important variables that are strong predictors of churn. These variables may also indicate why customers choose to switch to other networks.
- Even though overall accuracy will be your primary evaluation metric, you should also mention other metrics like precision, recall, etc. for the different models that can be used for evaluation purposes based on different business objectives. For example, in this problem statement, one business goal can be to build an ML model that identifies customers who'll definitely churn with more accuracy as compared to the ones who'll not churn. Make sure you mention which metric can be used in such scenarios.
- Recommend strategies to manage customer churn based on your observations.

Note that it's highly likely that you'll need to build multiple models to fulfil the objectives mentioned in Points 1 and 2.  Since here, you have a large number of attributes, and thus you should try using a dimensionality reduction technique such as PCA and then build a predictive model. After PCA, you can use any classification model.  

The above model will only be able to achieve one of the two goals - to predict customers who will churn. You can’t use the above model to identify the important features for churn. That’s because PCA usually creates components that are not easy to interpret.

Therefore, build another model with the main objective of identifying important predictor attributes which help the business understand indicators of churn. A good choice to identify important variables is a logistic regression model or a model from the tree family. 

**Steps**
- Data Understanding, Preparation, and Pre-Processing:
  1. Data understanding, identification of potentially useful and non-useful attributes and variable importance and impact estimation
  2. Data preparation, performing data cleaning, missing values imputation, outlier removal, and column level standardization (for e.g., date, etc.) into one format
 
- Exploratory Data Analysis:
  1. Performing basic preliminary data analysis including finding the correlation between variables and scatter plots to identify relationships between variables
  2. Performing advanced data analysis, including plotting relevant heatmaps, histograms, and basic clustering to find patterns in the data
 
- Feature Engineering and Variable Transformation:
  1. Feature engineering and performing one or more methods on attributes that can lead to the creation of a new potentially useful variable; for e.g., day from the date
  2. Variable transformation and applying categorical variable transformations to turn into numerical data and numerical variable transformations to scale data
 
- Model Selection, Model Building, and  Prediction:
  1. Identifying the type of problem and making a list of decisive models from all available choices
  2. Choosing a training mechanism; for e.g., cross-validation, etc., and tuning hyperparameters of each model
  3. Testing each model on the respective model evaluation metric
  4. Choosing the best model based on the fit of the data set and output variable
  5. Using ensemble options to improve the efficacy based on the evaluation metric stated in the problem

Dataset Link -> https://drive.google.com/file/d/1aUmUGLTXkQBOqTQb-E8pYlBSWLT9vgoc/view?usp=sharing
