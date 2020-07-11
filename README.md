# Sales_forecasting - Udacity Capstone Project
This repository, part of Udacity "Machine Learning Engineer" Nanodegree program contains my "Capstone Project".  
I choose to work on sales forecasting, with the Walmart dataset available in the data folder and on Kaggle with this link :  
https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting  
The dataset provide historical sales data for 45 Walmart stores located in different regions.   
Each store contains many departments, and participants must project the sales for each department in each store.

The proposal.pdf document provide more information about this projet:
- domain background
- problem statement
- benchmark model
- evaluation metrics
- project design

The Project_Report.pdf contains the major development stages of the project:
- Definition
- Analysis
    - Data exploration and Exploratory Visualization
    - Algorithms and Techniques
    - Benchmark models
- Methodology
    - Data Preprocessing
    - Implementation
    - Refinement
- Results
    - Model Evaluation and Validation
    - Justification
- Conclusion
    - Reflection
    - Improvement
    
All the code used for this project was made using the following Notebooks:
- Load and explore data : Data_Exploration.ipynb
- Create some benchmarks models, metrics, and Random Forest Model : Benchmark_and_RandomForest_Model.ipynb
- Test robustness of the RF Model : RF_Model-Robustness.ipynb
- Differents steps with AWS DeepAR. The 3 Notebooks are nearly the same with different parameter adjustments
    - train the model with data from 2 stores : DeepAR_2stores_train.ipynb
    - train the model with data from 2 stores adding one more feature : DeepAR_2stores_train_2features.ipynb
    - train the model with all data : DeepAR_Final_Model.ipynb

Python libraries used in this project:
- pandas : create and work data as table and time series
- numpy : manipulate arrays and for numerical computing
- matplotlib.pyplot : display graphics and scatter plots
- seaborn : display correlation heatmap
- datetime : convert data to date format
- sklearn.ensemble (RandomForestRegressor) : library with lots of algorithms for machine learning
- os : use operating system dependent functionnality
- json : convert Python dictionnaries or lists into JSON strings
- boto3 : work with or get info about AWS ressources
- sagemaker : AWS machine learning library
- pickle : to serialize and save the outputs of the deployed models
