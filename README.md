# Predictive-Modeling-Project
Description: 
This project involves using various models to predict wine quality using alcohol content in wines

## Project Overview
#### Motivation
>The goal of this project is to predict red wine quality based on its alcohol content using various machine learning models. This initiative addresses a critical business need within most industries, where understanding and predicting product quality is vital for producers, distributors, and retailers.
### Features
>Different Machine Learning techniques used were: Simple linear Regression, Multiple Linear Regression, Regression Trees, Support Vector regression, and Multiple Perceptron(MLP) modeling.
## Data
#### Data Source
>https://archive.ics.uci.edu/dataset/186/wine+quality <br>
>The Data in this project will be attached as 'qWine'
#### Data Structure
>The data mainly used in this project are: <br>
>>Quality: The quality of wine attached to each wine. <br>
>>Alcohol: The alcohol amount given in each wine.
## Technologies & Libraries
>VsCode(IDE)<br>
>JupyterNotebooks Extension<br>
>Python<br>
>Libraries: Pandas, Seaborn, Matplotlib, Sklearn, Statsmodels.api <br>
## Results & Analysis
#### Model Performance
>In this project, multiple machine learning models were tested to predict wine quality using alcohol content as the predictor variable. Among all the models evaluated, Support Vector Regression (SVR) with a hyperparameter setting of C=250 emerged as the most accurate. Key performance metrics for this model are as follows:
>**Mean Absolute Error (MAE): 0.036
>**Root Mean Squared Error (RMSE): 0.048<br>
>These results indicate that the SVR(C=250) model made predictions closest to the actual values with minimal error compared to other models. The low MAE and RMSE values demonstrate the model's ability to handle the complexity of the dataset effectively, capturing non-linear patterns in the relationship between alcohol content and wine quality.<br>
#### Business Data Science Implications
>This project exemplifies the critical application of predictive analytics in a business context, highlighting skills and methods essential for informed decision-making. Key takeaways include:<br>
##### 1. Optimizing Processes
> The accurate prediction of wine quality has implications for improving quality assurance procedures and streamlining resource allocation in the production process.
##### 2. Data-Driven Insights
>The focus on evaluation metrics like MAE and RMSE reflects a rigorous, data-driven approach to assessing model performance. This ensures reliability and minimizes errors in real-world applications.
##### 3. Business Applications
>Understanding the relationships between variables, such as alcohol content and wine quality, can drive strategic initiatives like forecasting demand, refining pricing strategies, and enhancing customer segmentation.
##### 4. Tailored Model Selection
>The selection and tuning of SVR(C=250) underline the importance of customizing models to meet specific business needs, ensuring that predictive solutions align with organizational goals.
#### Flexibility of the Approach
>While alcohol was used as the predictor variable in this project, the same methodology can be applied to predict wine quality using other variables (e.g., acidity, sugar content, pH levels, or sulfates). This flexibility ensures that the model can adapt to various feature sets, depending on the context and available data, making it a versatile tool for predictive analytics in the wine industry and beyond.


