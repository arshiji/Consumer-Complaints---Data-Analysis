BACKGROUND: CONSUMER COMPLAINT RESOLUTION

When consumers are not happy with some aspect of a business, they choose to reach out to customer service and might raise a complaint. Businesses try their best to resolve the complaints that they receive. However, it might not always be possible to appease every customer.

Unhappy consumers might raise follow-up questions/complaints about the resolutions provided, and this is detrimental to the business as it points to systemic failures in the Customer Support division and could lead to poor brand image. Disputed complaints which are being/have been resolved could be a critical dataset to derive essential learnings for any business.

Predicting whether a complaint resolution will be accepted or rejected by a consumer can enable a business to proactively look at complaints which might be disputed and hence save unnecessary escalation as well as their reputation. Systemic issues can be identified by noticing which complaints have a higher potential to be disputed, and customer support agents can be trained to pay more attention or enhance the quality of communication for certain types of complaints.


DATASET

You have been provided with a dataset containing the following columns –

- Date received: Date when the complaint was received
- Product: Type of product identified in the complaint, e.g., “Student loan”
- Sub-product: Type of sub-product identified in the complaint
- Issue: The issue raised in the complaint, e.g., “Struggling to repay your loan.”
- Sub-issue: E.g., “Problem lowering your monthly payments.”
- Consumer complaint narrative: This is a consumer-submitted description of “what happened”. Reasonable steps have been taken to remove personal information that could be used to identify the consumer
- Company public response: The response to a consumer’s complaint. It can be from a pre-set list of options, e.g., “Company believes the complaint is the result of an isolated error”
- Company: For which the complaint is about
- State: Derived from the consumer’s mailing address
- ZIP Code: Derived from the consumer’s mailing address
- Consumer consent provided: Flag to specify whether the consumer allowed the publishing of their complaint description
- Submitted via: E.g., “Web” or “Phone.”
- Date sent to the company
- Company response to consumer
- Timely response: Flag specifying if the response was timely
- Consumer disputed: Flag specifying if the consumer disputed the resolution
- Complaint ID
- Training Data: Edureka_Consumer_Complaints_train.csv
- Test Data: Consumer_Complaints_test.csv [Does not have the Consumer Disputed column]

TASK:
PART 1 - DATA EXPLORATION
PART 2 - TEXT-BASED MODELLING
PART 3 - CLASSIFICATION MODELS AND FEATURE ENGINEERING
       - Feature Engineering 
       - Model Training and Evaluation


Overview For Solution:
A set of Classification Algorithms were used. Both Boosting and Bagging methods were used for greater accuracy. 
My code trains all the ML Algorithms to obtain accuracy Values. The model needs to predict whether the customer will agree with the resolution given to him on his issue or not.
It then selects the Algorithm giving maximum accuracy and gives us the prediction.
NLP evaluation was also done for Text Based Modelling with Product and Consumer Complaints in the dataset.

Libraries Used:
- Pandas
- Numpy
- Scipy
- Seaborn
- Matplotlib
- Sklearn
- NLTK
- Machine Learning models used:
- Logistic regression
- KNN 
- Decision Tree Classifier
- Random Forest Classifier
- Gaussian Naiver Bayer
- SVM
- Voting Classifier
- Hyperparameter Tuning and Boosting models used:
- GridSearchCV
- Kfold Validation
- AdaboostCLassifier


The flow of code is as follows:
- DataCollection
- Data Pre-processing 
- Null value handling
- Univariate analysis
- Multivariate analysis
- Data encoding
- Data scaling
- Multicollinearity evaluation
- Smote analysis
- Feature Engineering
- DateTime columns handling
- New feature creation
- Text-based feature engineering
- Train-test split for validation of models being trained
- Training with ML algorithms
- NLP text-based modelling
- Classification models used for training and prediction
- Clustering models used
- Boosting and Bagging algorithm based models used for prediction
- Validations and prediction 
