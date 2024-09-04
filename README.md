# Laptop_Price_Predictor
# Project Overview :
In this project i have done a new analysis on a dataset of laptop specification and created a model about prediction of laptop price and exported it into an app . My project includes use of machine learning models which tries to predict the price of laptop based on the inputs provided by user . 

# DataSet :

The dataset used for this project was sourced from Kaggle and includes detailed information about the laptops . 
Key features :
1. Brand : Name of Laptop Brand like Apple , Dell , Lenovo
2. Size : Laptop screen size in inches
3. Screen resolution
4. Processor : Processor of the laptop (eg. i3,i5,i7 etc)
5. Ram : Ram for the laptop (like 4gb , 8gb)
6. Memory : Wheather the memory is hdd or ssd and the size of hdd/sdd
7. Os
8. Price of the laptop (Target feature of our dataset)

# Project Workflow :
1. The project begins with obtaining a comprehensive dataset from Kaggle, which includes various features related to laptop specifications and their corresponding prices. The first step involves data preprocessing, where I meticulously cleaned the dataset to handle missing values, outliers, and irrelevant data. Feature extraction was performed to derive valuable insights from existing features, enhancing the predictive power of the model.
2. To understand the underlying patterns in the dataset, I visualized the data using histogram , scatterplot , displots etc., which helped in identifying trends and distributions of key features.
3. For the machine learning model development, I experimented with multiple regression techniques including Linear Regression, Lasso, Ridge, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM). After comparing the performance of these models, I implemented an ensemble learning approach using a Voting Regressor to combine the strengths of the individual models.
4. I evaluated the model's performance using Mean Absolute Error (MAE) and R-squared (R2) score, ensuring a robust and accurate price prediction system.
5. Once the optimal model was identified, I exported it using the Pickle module, making it ready for deployment in a web application.
6.  I then created a user-friendly web app using the Streamlit package, allowing users to predict laptop prices based on input features.



