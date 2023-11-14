# **Board Game Behavior: An Analysis of Demographics and Gameplay Preferences**

## **Authors**:
Dario Leyva-Brown, Marie Lawler, Seven Lewis

## **Question:** How do demographics relate to an individual's exposure to board games?

## **Data:**

The data we are using for our project will be gathered genuinely through survey. The data does is exist but will take some amount of time to acquire. 

As of November 6th, 2023, we have 40 responses to our survey but plan to reach around 250 to 500 responses.

The data itself will be structured as individual response rows with each feature being a different question. The survey questions inquire about the following demographics:
- Student/Faculty Member Status
- Gender Identity
- Age
- Race
- Employment Status
- Corrective Vision
- Religiosity
- Area of Study

And the following board game questions:
- Enjoyment of Board Games
- \# of Board Games Owned
- Frequency of Board Game Play
- Style of Player
- Desirable Gameplay Elements
- Enjoyed Board Games
- Scale Rating of Chess
- Desirable Board Game Genres

## **Goal:**

We will use Python for exploratory data analysis, data visualization, and machine learning. This will be used to find patterns among demographics and board games as well as predict ones exposure to board games given a specific set of demographics. 

## Milestone 1 Deliverable (11/18/23):

Criteria for Milestone 1 achievement (otherwise, we will pivot):
 - Minimum data acquired (at least 100 responses)
 - A data cleaning pipeline will have been established
 - An exploratory analysis pipeline will have been built for current and future responses
    - Results must not appear trivial or null
 - A descriptive write-up for the current stage of the project will have been produced

If these criteria are not met, we will submit an alternative initial project deliverable alongside Milestone 1 using a backup dataset.

## Milestone 2 Deliverable (12/2/23):

 - Complete and refine the exploratory analysis
 - Finalize the predictive model

## Roadmap:

 - Survey Data Collection: **Seven**
    * Finalize survey form (complete)
    * Distribute survey to target audience (complete by Milestone 2)
    * Monitor and encourage responses weekly (on-going)
 - Data Cleaning: **Marie**
    * Establish data cleaning protocols (by Milestone 1)
    * Implement initial data cleaning on first 100 responses (by Milestone 1)
    * Ongoing cleaning for additional data collected (complete by Milestone 2)
 - Exploratory Analysis/Visualization: **Dario**
    * Develop initial exploratory data analysis pipeline (by Milestone 1)
    * Create initial set of visualizations (by Milestone 1)
    * Iterate and improve with additional data (by Milestone 2)
 - Predictive Modeling: **Seven**
    * Begin model selection and initial testing (by Milestone 2)
    * Train preliminary models (by Milestone 2)
    * Fine-tune final model(s) and validate (by Milestone 2)
 - Project Write-up and Summary: **Marie** 
    * Outline main sections for write-up (by Milestone 1)
    * Compile findings and analysis for Milestone 1 (by Milestone 1)
    * Finalize comprehensive write-up incorporating predictions (by Final)



### Expanded Content for Machine Learning and Exploratory Data Analysis Descriptions:

**Exploratory Data Analysis:**
- The initial analysis will involve computing summary statistics for demographic and board game preference variables.
- We will use a combination of visualizations such as histograms, box plots, and scatter plots to uncover distributions and relationships in the data.
- We plan to investigate correlations between demographics and preferred game genres.
- Further exploration may include clustering techniques to identify distinct gamer profiles based on survey responses.

**Machine Learning:**
- We will experiment with a range of classifiers to predict demographic information from gameplay preferences and vice versa.
- Potential models include Random Forest, Linear Regression, and k-nearest neighbor.
- We will conduct hyperparameter tuning to optimize model performance.
- We aim to evaluate models based on accuracy and R2 score.