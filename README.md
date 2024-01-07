# Bank Customer Churn Prediction Project

This project aimed to predict customer churn for a bank. It involved `data preprocessing`, `exploratory data analysis`, `feature selection` `feature engineering`,  and `evaluating machine learning models`. The analysis provided key insights such as geographic distribution of customers, churn percentage, credit card usage impact, customer complaint influence, and churn likelihoods among different age groups. The findings can guide the bank in developing strategies for customer retention and minimizing revenue loss.

## 1. Data Preprocessing:
Before performing `exploratory data analysis`, we conducted preprocessing steps to ensure the quality of the dataset. We checked for null values, duplicate values, and reviewed the data types of each feature. Fortunately, there were no null or duplicate values in the dataset, and all the data types were appropriate for analysis. This preprocessing step ensured the integrity and reliability of the data for further analysis.

## 2. Exploratory Data Analysis:
In exploratory data analysis (EDA), a comprehensive approach is taken to understand the dataset. It involves conducting descriptive statistics, segmenting the data into groups for better analysis, and utilizing various graphical visualizations like bar plots, pie charts, and KDE plots. These visualizations provide valuable insights and facilitate easy comprehension of the data, aiding in more informed decision-making. EDA leaves no gaps, covering all essential aspects to gain a thorough understanding of the dataset.

## 3. Feature Selection and Engineering:
To optimize our dataset for machine learning models, we performed `feature selection` and `feature engineering`. `SelectKBest` and `chi2` techniques were used to identify the `top 5 features` influencing churn. Additionally, categorical features were encoded using `label encoder`. This process ensured that our models would receive the most relevant and informative features, improving their predictive power.

## 4. Model Building and Evaluation:
Multiple machine learning algorithms, including `logistic regression`, `decision trees`, `random forests`, `XGBoost`, and `stacking techniques`, were implemented for churn prediction. The models were trained on the preprocessed dataset and evaluated using various metrics like `accuracy`, `precision`, `recall`, `F1-score`, and `area under the curve (AUC)`. This evaluation allowed us to assess the performance of each model and select the most suitable one for customer churn prediction. It was observed that the tree-based algorithms performed better in this dataset.

## 5. Key Insights:
After conducting our analysis, we gained several key insights that can guide the bank in reducing customer churn:

- **Geographic distribution:** The majority of customers are from France. This information can help the bank tailor its marketing and retention strategies based on regional preferences and needs.

- **Churn percentage:** Approximately `80%` of customers did not churn. The bank can focus on retaining these customers by offering personalized services and incentives to enhance their loyalty.

- **Credit card usage:** Around `70%` of customers have a credit card, and these customers show a lower probability of churning. The bank can prioritize credit card holders and offer additional benefits to encourage their continued engagement.

- **Customer complaints:** About `20%` of customers have complained, and there is a high probability of churn among these customers. Identifying the reasons behind these complaints and addressing them will be crucial for reducing churn rate.

- **Age groups:** Customers in the age range of `31-40` form the majority, while the age range of `51-60` exhibits a higher likelihood of churning. The bank can use this information to tailor its services and communication to specific age groups, improving customer satisfaction and retention.

## 6. Conclusion:
In conclusion, our analysis provides valuable insights into customer churn prediction for a bank. By leveraging machine learning algorithms and exploring key factors influencing churn, the bank can develop targeted strategies to retain customers and minimize revenue loss. The findings from this analysis can serve as a foundation for future research and initiatives aimed at customer retention and satisfaction.
