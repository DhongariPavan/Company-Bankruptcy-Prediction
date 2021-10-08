# Bankruptcy-Prediction
Using different machine learning techniques to train a model to predict bankruptcy of companies.
# Corporate-Bankruptcy-Prediction

![image](https://user-images.githubusercontent.com/85662956/132116974-e9f2c605-09f0-4ae2-be4b-8847ac1f12ab.png)

### Predict the bankruptcies of certain companies listed on Taiwan Stock Exchange using data collected from the Taiwan Economic Journal for the years 1999 to 2009.


### 💾 Project Files Description This Project includes 1 ipynb notebook and 1 input CSV file:

### IPython Notebook:

CAPSTONE_COMPANY_BANKRUPTCY_PREDICTION(FINAL_COLAB).ipynb - Final IPython Notebook with explanation of steps in markdown.

### Input Files:

Copy of COMPANY BANKRUPTCY PREDICTION.csv - Input dataset having information about different shows/movies available on Netflix.


### 📖 About the Project :

Predicting the financial health of companies and firms has become one of the key interests for their owners, creditors and all the stakeholders alike, especially now when huge amounts of financial data can be stored and analysed on computers.

The purpose of such a predictive model which tries to foreseee the bankruptcy is to combine various econometric parameters that can effectively guage the financial state of a company and enable the management to take pre-emptive measures that can potentially help to avoid any financial distress to the company.

### 📖 Project Description :

In this project we present our analysis of the data at hand as we go on selecting various subsets of the huge feature space available to us. We try to compile and compare each and every result as we step from a niave modelling to a more nuanced and standard one. We have employed some of the most widely used classification algorithms for this project namely;

<b>
  
  1. Isolation Forest for anamoly detection
  
  2. Guassian Naiye Bayes
  
  3. Logistic Regression
  
  4. Random Forest
  
  5. Balanced Bagging
  
  6. SMOOTEEN based XGB
  
  7. Easy Ensemble Technique
  </b>
  
  We began our analysis by visualizing the sparsity of the two target classes (bankrupt and non-bankrupt) in our dataset. Once we were assured of the huge class imbalance in the data we were going to work on, we began to speculate that the prediction could very well be an anamoly detection problem.
  
  We used box plots to visualize how each feature was distributed over each of the two target classes. This gave us a clear idea as to which variable was contributing more to the bankruptcy.
  
  As we delved deep into the dataset it become increasingly clear that the classes had a rich overlap and hence could barely be modelled into an anamoly detection.
  
  Towards the begining, our approach mainly included reducing the dimensionality of the dataset and getting an ideal number of features which could be modelled with ease and effeciency. We employed some of the most commonly used feature engineering techniques like; <b> Threshold Variance, Information Gain, Random Forest, Lasso </b> and a few others to subset our feature space and remove the ominous curse of dimensionality.
  
  Finally we started the machine learning part on the choosen feature subsets, did cross validation for each of the models' hyperparameters and recorded the performance in each case into a compact dataframe. The evaluation metrics we chose for our project include <b> roc_auc score, precision, recall, f1-score. </b>

### 📋 Execution Instruction :

The given IPython Notebook can be either downloaded to be run on your local Jupyter Notebook or can be directly run on Google Colab.

### 📜 Credits :

Dhongari Pavan | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

Contact me for Data Science Project Collaborations

### 📚 References :

https://machinelearningmastery.com/feature-selection-with-real-and-categorical-data/

https://www.kdnuggets.com/2020/12/machine-learning-anomaly-detection-conditional-monitoring.html
