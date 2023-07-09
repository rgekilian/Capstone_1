§
# Module 11—Draft the Problem Statement

## Requirements

In Module 11, you will define your problem statement and develop a prospectus of the project. The prospectus provides a general overview of the question you will be asking, what data you think you will need to answer the question, and the techniques you might use to answer the question. This submission is pass/fail because it is expected that your plan will change based on your facilitator’s feedback.

Submission contained a question and a data source

It is time to start putting your creativity and domain-specific knowledge to use. Your capstone project will be a question of your own design where you answer a question in your specific field (or the field you want to move into). For this initial submission, all you need to submit is:

    A general idea of your question (a sentence or two)
    An initial guess at what data you will need to answer that question
    An initial guess as to how you will source that data

Notice what is missing in this initial post. You DO NOT have to suggest what technique you will use to find the answer. This omission is on purpose. Your initial submission here is a place to start your conversation with your Learning Facilitator. Over the next few weeks, your Learning Facilitator will have a 1:1 session with you to refine your question, discuss your data (and where to source it), and brainstorm techniques you might use to address your question.

This is a required assignment and counts toward program completion.
Submission Instructions:

    Submit your text or upload a file to start a conversation with your Learning Facilitator
    You may attempt this activity as many times as you wish until the due date
    Your submission will be graded as complete/incomplete

## Submission

We aim to examine the factors influencing corruption levels across different countries,  with the Corruption Perceptions Index (CPI) as the target variable. The data required includes indicators such as GDP, education level, political stability, income inequality, rule of law, Human Development Index, freedom of the press, unemployment rates, and population demographics. These data can be sourced from Transparency International, the World Bank, World Justice Project, Reporters Without Borders, UNDP, and various national statistical agencies.

# Module 17—Problem Statement

## Requirements

Links to an external site. file, you will submit your formal problem proposal, including:

    Research question you intend to answer
    Expected data sources and structure
    Expected results
    Expected techniques

Write a formal problem proposal, including:

- The research question you intend to answer (one sentence, if possible)
- Your expected data source(s) (either a link to existing data or a sentence describing where you will source the data from)
- The techniques you expect to use in your analysis
- The expected results
- Why this question is important

Using the provided fololowing structure:
<!-- 
        ### Project Title

        **Author**

        #### Executive summary

        #### Rationale
        Why should anyone care about this question?

        #### Research Question
        What are you trying to answer?

        #### Data Sources
        What data will you use to answer you question?

        #### Methodology
        What methods are you using to answer the question?

        #### Results
        What did your research find?

        #### Outline of project

        - [Link to notebook 1]()
        - [Link to notebook 2]()
        - [Link to notebook 3]()

        ##### Contact and Further Information 
-->

## Submission

### Insights into Corruption: A Machine Learning Approach to Identify Influencing Factors

**Author**: Renaud Kilian

#### Executive Summary

This project aims to identify and understand the various socio-economic and political factors influencing the Corruption Perceptions Index (CPI) at a country level. The exploration of these potential indicators might provide valuable insights into developing effective strategies to mitigate corruption and promote transparency and accountability in public sectors globally.

#### Rationale

Corruption is a pervasive issue that significantly affects economies and societies. Understanding its drivers is crucial for policy-making, international development, and global governance. This analysis can help in formulating more effective anti-corruption strategies and improving the transparency and accountability of public administrations worldwide.

#### Research Question

What are the significant socio-economic, political, and demographic factors influencing the Corruption Perceptions Index at a country level?

#### Data Sources

The necessary data will be sourced from the following:

1. [Corruption Perceptions Index (CPI)](https://www.transparency.org/en/cpi) - Transparency International
2. [World Development Indicators (WDI)](https://databank.worldbank.org/source/world-development-indicators) - World Bank's Open Data

#### Methodology

Our methodology will align with the CRISP-DM framework, which involves six major phases: Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, and Deployment.

**Business Understanding:** We will start by defining the problem and setting the project objectives, which in this case is identifying the socio-economic, political, and demographic factors that influence the Corruption Perceptions Index at a country level.

**Data Understanding:** We will gather the necessary data from various sources like Transparency International, World Bank's Open Data, World Justice Project, Reporters Without Borders, UNDP, and country-specific statistical agencies. Initial data exploration will help us understand the data's quality, completeness, and relevance to our research question.

**Data Preparation:** The collected data will be pre-processed and cleaned to handle missing values, outliers, and potential transformations. This phase includes data integration where data from different sources is combined, and feature engineering to create new variables if required.

**Modeling:** We plan to experiment with various regression models including Multiple Linear Regression, Decision Tree Regression, Random Forests, Gradient Boosting, and potentially Ridge or Lasso if multicollinearity is found among predictors. Feature selection techniques will be applied to identify the most relevant predictors.

**Evaluation:** Models will be assessed based on relevant metrics such as R-squared, Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE). Cross-validation techniques will be used to ensure model robustness and avoid overfitting.

**Deployment:** Once the best model is selected, it will be used to derive insights about the factors influencing corruption. The final model, code, and findings will be documented and shared for future use and reference.

#### Expected Results

We anticipate identifying a set of significant variables that contribute to the corruption level in a country. These factors might include socio-economic variables like GDP, income inequality, education, along with political factors such as political stability, rule of law, and press freedom.

##### Contact and Further Information

For any inquiries or further information, please reach out to [kilren@gmail.com](mailto:kilren@gmail.com).

# Module 20—Initial Report and EDA

In Module 20, you will submit your findings, including:

    Jupyter notebook where you did the work
    Project template (README.md 

Links to an external site.) with completed results section

<!-- 
        ### Project Title

        **Author**

        #### Executive summary

        #### Rationale
        Why should anyone care about this question?

        #### Research Question
        What are you trying to answer?

        #### Data Sources
        What data will you use to answer you question?

        #### Methodology
        What methods are you using to answer the question?

        #### Results
        What did your research find?

        #### Outline of project

        - [Link to notebook 1]()
        - [Link to notebook 2]()
        - [Link to notebook 3]()

        ##### Contact and Further Information 
-->

## Submission

### Insights into Corruption: A Machine Learning Approach to Identify Influencing Factors

**Author**: Renaud Kilian

#### Executive Summary

This project aims to identify and understand the various socio-economic and political factors influencing the Corruption Perceptions Index (CPI) at a country level. The exploration of these potential indicators might provide valuable insights into developing effective strategies to mitigate corruption and promote transparency and accountability in public sectors globally.

#### Rationale

Corruption is a pervasive issue that significantly affects economies and societies. Understanding its drivers is crucial for policy-making, international development, and global governance. This analysis can help in formulating more effective anti-corruption strategies and improving the transparency and accountability of public administrations worldwide.

#### Research Question

What are the significant socio-economic, political, and demographic factors influencing the Corruption Perceptions Index at a country level?

![Corruption Perceptions Index](images/animated_map.gif)

#### Data Sources

The necessary data will be sourced from the following:

1. [Corruption Perceptions Index (CPI)](https://www.transparency.org/en/cpi) - Transparency International
2. [World Bank Indicators](https://databank.worldbank.org/source/world-development-indicators) - World Bank's Open Data

#### Methodology

Our methodology will align with the CRISP-DM framework, which involves six major phases: Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, and Deployment.

**Business Understanding:** We will start by defining the problem and setting the project objectives, which in this case is identifying the socio-economic, political, and demographic factors that influence the Corruption Perceptions Index at a country level.

**Data Understanding:** We will gather the necessary data from various sources like Transparency International, World Bank's Open Data, World Justice Project, Reporters Without Borders, UNDP, and country-specific statistical agencies. Initial data exploration will help us understand the data's quality, completeness, and relevance to our research question.

**Data Preparation:** The collected data will be pre-processed and cleaned to handle missing values, outliers, and potential transformations. This phase includes data integration where data from different sources is combined, and feature engineering to create new variables if required.

**Modeling:** We plan to experiment with various regression models including Multiple Linear Regression, Decision Tree Regression, Random Forests, Gradient Boosting, and potentially Ridge or Lasso if multicollinearity is found among predictors. Feature selection techniques will be applied to identify the most relevant predictors.

**Evaluation:** Models will be assessed based on relevant metrics such as R-squared, Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE). Cross-validation techniques will be used to ensure model robustness and avoid overfitting.

**Deployment:** Once the best model is selected, it will be used to derive insights about the factors influencing corruption. The final model, code, and findings will be documented and shared for future use and reference.

#### Expected Results

We anticipate identifying a set of significant variables that contribute to the corruption level in a country. These factors might include socio-economic variables like GDP, income inequality, education, along with political factors such as political stability, rule of law, and press freedom.

##### Contact and Further Information

For any inquiries or further information, please reach out to [kilren@gmail.com](mailto:kilren@gmail.com).

# Module 24—Technical Report and Presentation

In Module 24, you will submit your technical report. Your technical report will be an organized and well-structured GitHub repository with an informative README and collection of Jupyter Notebooks that walk through your analysis. In addition to your technical notebooks, you will compress the information into a non-technical presentation that covers your problem, solutions, important findings, and suggestions for next steps.
