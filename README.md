# Movie Revenue Prediction

We try to predict movie revenue.

Several things to note

- `variable_name` to name a variable eg `revenue_in_usd`
- `function_name` to name a function eg `def get_revenue_in_usd`
- `Class ClassName` to name a class eg `Class TextWrangler`
- let's write more function so we can re-use it
- let's keep the function name, Class name and variable name explanatory enough
  <br />
- let's keep all our import in the second cell

1. Project Setup and Data Collection: ✅
    - 1.1 Set up your Jupyter notebook ✅
    - 1.2 Scrape or pull data from online resources ✅
    - 1.3 Load the data into your notebook ✅ <br /><br />

2. Exploratory Data Analysis (EDA):
    - 2.1 Initial data inspection (shape, info, describe) ✅
    - 2.2 Generate and save pandas profiling report ✅
    - 2.3 Visualize data distributions ('IMDB Rating', 'Budget', 'Gross Worldwide', 'Runtime') ✅
    - 2.4 Explore relationships between 'Gross Worldwide' and other variables ✅
    - 2.5 Analyze categorical data ('Directors', 'Writers', 'Stars', 'Origin Countries', 'Languages', 'Genres') ✅
    - 2.6 Identify potential issues (missing values, duplicates)<br /><br />

3. Data Cleaning and Preprocessing:
    - 3.1 Handle missing values
    - 3.2 Remove duplicates
    - 3.3 Correct data types (ensure 'Budget' and 'Gross Worldwide', 'Runtime', etc. are numerical)
    - 3.4 Handle outliers:
        - 3.4.1 Detect outliers (boxplots and IQR)
        - 3.4.2 Apply treatment methods:
            - Quantile-based Flooring and Capping
            - Trimming
            - Log Transformation
    - 3.5 Compare and discuss outcomes of outlier treatments<br /><br />

4. Feature Engineering:
    - 4.1 Encode categorical variables ('Directors', 'Writers', 'Stars', 'Origin Countries', 'Languages', 'Genres' etc)✅
    - 4.2 Extract features from 'Storyline' using NLP techniques (optional)✅
    - 4.3 Create new features if applicable (e.g., director/star popularity, genre combinations) (optional) ✅
    - 4.4 Normalize/standardize numerical features if needed<br /><br />

5. Feature Selection:
    - 5.1 Identify most important features for predicting 'Gross Worldwide' / revenue_in_usd ✅
    - 5.2 Use correlation analysis or feature importance techniques ✅ <br /><br />

6. Natural Language Processing (if applicable):
    - 6.1 Text data cleaning ✅
    - 6.2 Tokenization ✅
    - 6.3 Stop word and punctuation removal ✅
    - 6.4 Stemming or lemmatization ✅ <br /><br />

7. Model Selection and Training:
    - 7.1 Split data into training and testing sets
    - 7.2 Select and train multiple regression models (e.g., Linear Regression, Random Forest, Gradient Boosting)
    - 7.3 Perform cross-validation<br /><br />

8. Results and Visualization (based on regression models):
    - 8.1 Create meaningful visualizations of your findings (e.g., actual vs predicted revenues)
    - 8.2 Interpret and explain results<br /><br />

9. Unsupervised Learning:
    - 9.1 Select and apply two unsupervised learning methods
    - 9.2 Analyze and interpret results
    - 9.3 Compare outcomes of different methods
    - 9.4 Create a feature from this cluster generated and put it into the regression model
    - 9.5 Analyse the result from the new feature you engineered  <br /><br />

10. Results and Visualization (based on unsupervised learning):
    - 10.1 Create meaningful visualizations of your findings (e.g., actual vs predicted revenues)
    - 10.2 Interpret and explain results<br /><br />

11. Conclusion and Recommendations:
    - 11.1 Summarize key findings
    - 11.2 Discuss the most influential factors for movie revenue
    - 11.3 Provide actionable insights or recommendations<br /><br />

12. Documentation and Reporting:
    - 12.1 Ensure clear markdown explanations throughout the notebook
    - 12.2 Prepare the final PDF report
    - 12.3 Compile all deliverables (notebook, data, profiling report, PDF report)<br /><br />
