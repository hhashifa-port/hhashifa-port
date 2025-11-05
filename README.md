## Hello!

<!--
**hhashifa-port/hhashifa-port** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...

- 
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...

- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

I'm Hasna Hashifa! I’m a Mathematics graduate with a deep passion for Data Science. I truly enjoy delving into data—exploring, learning, and developing my skills in building data pipelines and predictive models. I’m highly motivated to apply my knowledge to real-world cases, where I can gain hands-on experience and uncover valuable insights that drive better decision-making. Let's connect and explore the world of data together, I'm always happy to learn and improve! :D

Here are a few things about me:

- 🌱 Areas I'm currently exploring are: <br>
  Data Wrangling (or Cleaning), Exploratory Data Analysis, Statistical Analysis, Data Visualization, Machine Learning Modeling (focused on supervised and unsupervised learning; currently exploring NLP and machine learning applied to unstructured data), Model Evaluation and Hyperparameter Tuning.
  
- 🔭 Tools I often work with are: <br>
  Python, SQL (Postgre), Tableau (or Power BI), Microsoft Office Product (include Microsoft Excel).
  
- 📫 Feel free to reach me via mail: hhashifa@gmail.com

- 👯 Here’s a summary of my hands-on experience: <br>

The projects I worked on while learning data science. There are still many things that could be improved, so I’ve added some notes for future improvements.

|Project|Goals|Area|Libraries Used|Project Description|Notes|
|-------|-----|----|--------------|-------------------|-----|
|[Online Shoppers Purchasing Intention](https://github.com/hhashifa-port/Online-Shoppers-Purchasing-Intention)|This project aims to predict whether a user visiting an online store during a given session will make a purchase, using data collected from user interactions and session behavior.|Supervised Learning - Classification|pandas, numpy, matplotlib, seaborn, scikit-learn, shap| - **Exploratory Data Analysis (EDA)**: Explored and visualized the data to understand its statistics and uncover insights useful for both modeling and business interpretation. <br> - **Data Preprocessing**: This step covered *data cleaning, feature encoding, feature engineering, feature selection,* and *feature transformation* — making sure the dataset was fully numeric before training. <br> - **Machine Learning Modeling and Evaluation**: Trained and compared several models, including Logistic Regression, KNN, Decision Tree, Random Forest, AdaBoost, and XGBoost, while analyzing learning curves to fine-tune the hyperparameters.| - Make sure to understand every feature so the analysis results aren’t misinterpreted. <br> - To avoid data leakage, do the exploratory data analysis (EDA) only on the training data. <br> - Be careful when doing feature encoding, especially for nominal and categorical features.|
|[Human Resources Analytics](https://github.com/hhashifa-port/Human-Resources-Analytics)|The goal of this project is to analyze and visualize the characteristics of employees who decide to leave the company and those who stay, and to explore what factors might influence their decisions based on the given dataset.| - Python for Analysis and Visualization <br> - Canva for making reports (non-interactive dashboard)|pandas, numpy, matplotlib, seaborn, scipy|Focused on analyzing employee attrition data and creating visualizations in Python using Matplotlib and Seaborn. The analysis was performed on a dataset that had been cleaned and aggregated to make it ready for exploration.|Reports created in a non-interactive format are less useful for up-to-date decision making. It would be more effective to build an interactive multi-page dashboard, where each page focuses on some specific KPIs to be presented.|
|[Airline Customer Value Analysis](https://github.com/hhashifa-port/Airline-Customer-Clustering)|The project aimed to analyze customer value in an airline company and create actionable clusters that could inform the next steps in marketing campaigns.|Unsupervised Learning - Clustering|pandas, numpy, matplotlib, seaborn, scikit-learn, scipy|Conducted customer segmentation using K-Means clustering combined with Principal Component Analysis (PCA), resulting in four distinct clusters. The insights from each cluster can guide the next marketing campaigns for more precise targeting.| - Ensure a clear understanding of the meaning of each feature in the dataset, so that data preprocessing and interpretation are accurate. <br> - Verify that the data meets the requirements for modeling using K-Means and PCA. <br> - Conduct further analysis on the clustering results to identify the most effective clusters, which can then be used to design data-driven marketing campaigns.|
|[Telecom Customer Churn](https://github.com/hhashifa-port/Telecom-Customer-Churn)|Built a machine learning model to predict whether a customer will churn or not.|Supervised Learning - Classification|pandas, numpy, matplotlib, seaborn, scikit-learn, scipy| - **Data Validation**: Ensured that each feature in the dataset accurately represents its intended meaning and has the correct data type. <br> - **Exploratory Data Analysis (EDA) on Training Data**: Focused on understanding the characteristics of the data in preparation for modeling. <br> - **Data Preprocessing and Cleaning on Training Data**: Executed insights gained from the EDA process to prepare the data for modeling. Steps included imputation, feature selection, encoding, creating new features, and handling class imbalance in the dataset. <br> - **Modeling and Evaluation**: Applied Logistic Regression, K-Nearest Neighbors (KNN) Classifier, Decision Tree, Random Forest, and XGBoost. Evaluation focused on Recall and ROC-AUC metrics.|The next step could involve customer segmentation to identify specific strategies to reduce churn within each segment.|
[Raw: Customer Insights for E-Commerce](https://github.com/hhashifa-port/Customer-Insights-for-E-Commerce)|This project analyzes the characteristics of customers from a certain e-commerce.| SQL and Tableau || There's no missing values nor duplicates data. Whereas, SQL used for data validation such as data type and inconsistent formatting, merged information from one to another database.|| 
[Fraud Detection Analysis](https://github.com/hhashifa-port/Fraudulent-Transaction-Prediction)|Built a model to predict whether a transaction is fraudulent or not.|Supervised Learning - Classification|os, json, numpy, pandas, matplotlib, searborn, scikit-learn, scipy, garbage-collector (since the data size are huge)| - **Data Collection and Preparation**: Combined data from multiple CSV and JSON files into a single, unified dataset containing all relevant information from the original files. <br> - **Data Splitting**: Divided the dataset into training, validation, and test sets. <br> - **Exploratory Data Analysis (EDA) on Training Data**: Performed statistical and technical analysis, as well as an investigation of the relationship between each feature and the target variable, is_fraudulent. <br> - **Data Preprocessing**: Conducted feature engineering, outlier detection using Isolation Forest, standardization, encoding of categorical features, and feature correlation and selection. <br> - **Data Modeling**: Implemented machine learning models including Logistic Regression, Decision Tree, Random Forest, and XGBoost, with hyperparameter tuning focused on AUC metrics.|Fraud detection can be challenging since fraudulent transactions are rare and may appear as outliers. Given the small proportion of fraud cases, using the F1 score is advisable to reduce the risk of incorrectly labeling fraudulent transactions as non-fraudulent.|
