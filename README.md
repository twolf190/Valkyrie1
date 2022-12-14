# Valkyrie1
Git Repo for Data Science Project with FAA. George Mason University Graduate Students, Team Valkyrie. 

For our research we are focused on classifying three different Helicopter Maneuvers: Surface Taxi, Hover Taxi, Quick Stop 

## EDA
The Exploratory Data Analytics (EDA) section of this repository is where our team first ingested flight data from the FAA's RoaR simulator. We plot the data various ways to explore patterns and impacts on different maneuvers of interest that we are studying. 

## Machine Learning
The Machine Learning process team Valkyrie used can be summarized in the flow chart at the bottom of this section. The process starts with the FAA sending us .csv files from the RoaR simulator. From there we ingest and process the data to our notebooks. Once we have the data formated the way we want it we balance our classes and train our models. Models are tuned based on their test/validation scores and eventually output a prediction. 

**Machine Learning Algorithms Used:** Decision Tree, SVM, XGBoost, Logistic Regression, Neural Network

For more details on our machine learning process feel free to inspect the code or read the Machine Learning section in our Project Report. 

![image](https://user-images.githubusercontent.com/71101663/204165475-c6eaef49-b459-481f-9e41-d51f73596038.png)

### Decision Tree
Decision Tree uses the team’s selected ROAR file variables combined with flight logs to predict which maneuver is being performed (surface taxi, hover taxi, or quick stop). Decision trees are useful because they can handle multi-class classification, are visually easy to interpret by those unfamiliar with machine learning, and they can handle null values (although that does not apply in our case).

### Support Vector Machine (SVM)
The Support Vector Machine algorithm is being used to leverage linear separable relationships to classify our maneuvers. In a SVM model, a hyperplane is fitted in between the fields of the data. The data points closest to this hyperplane are called the support vectors. The patterns in the data that are revealed by the hyperplane are what is used to make classifications. 

### Extreme Gradient Boosting (XGBoost)
Extreme Gradient Boosting, or XGBoost as it is commonly referred to, is a gradient-boosted decision tree (GBDT) machine learning model. Gradient-boosting involves the input of multiple decision tree models, with each iteration learning from the previous tree model. XGBoost models are a combination of multiple iterations of GBDTs and software/hardware optimization efforts.

### Logistic Regression 
Logistic regression is a linear classifier used to depict the relationship between a discrete dependent variable and one or more independent predictor variables. It is used for classifying the dependent or target variable into one of a set number of outcomes. It is a relatively simple machine learning algorithm that is easy to implement for predictive analytics, provided exploratory data analysis is performed first on the datasets to refine the selection of feature variables. 

### Neural Network
A neural network is a non-linear regression method that teaches computers to process data in a way that is loosely inspired by the human brain. It is a deep learning ML method that uses interconnected nodes or neurons in a layered structure that resembles the human brain. Using algorithms, the computing system can recognize hidden patterns and correlations in raw data, cluster and / or classify it, and continuously learn and improve over time. A linear combination is first applied to combine all the predictors in the dataset into an input to a hidden unit. A non-linear function is then applied to transform the linearly combined predictors and obtained as the output from the hidden unit. Neural networks are versatile since they can learn and model relationships between complex inputs and outputs that are nonlinear.
