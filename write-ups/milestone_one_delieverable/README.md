
# **Milestone 1:** Board Game Behavior: An Analysis of Demographics and Gameplay Preferences

 
## **Authors**:
Dario Leyva-Brown, Marie Lawler, Seven Lewis

# Current Completion

**Fulfillment of Non-Pivot Conditions (as detailed in Initial Project Proposal):**

- [x] Minimum data acquired (at least 100 responses)

- [x] A data cleaning pipeline has been established  
    
- [x] An exploratory analysis pipeline will have been built for current and future response
  - Results do not appear null

- [x] A descriptive write-up for the current stage of the project will have been produced

**More Descriptive Explanation of Data Cleaning and Exploration:**
- [Data Cleaning](data_curation_readme.md)
  - Drop metadata (ID, Start time, Completion time, Email, Name, Last modified time).
  - Rename raw fields from question to concise descriptions.
  - Take the multiselect questions (Race, Desirable Gameplay Elements, Desirable Board Game Genres) and expand them to bit/bool field features.
    - For instance, the "Desirable Gameplay Elements" feature expands to:
      - Conflict/CompetitionIsPreferredElement
      - CooperationIsPreferredElement
      - LuckIsPreferredElement
      - ...
  - Manually bucket answers to "Area of Study", transforming a bunch of difficult to parse strings into categorical values like "STEM", "Arts & Humanities", and "Social Studies".
  - Shorting the answer choices for "Style of Player" to something concise for data analysis purposes.
- Data Exploration 
  - TODO

## Artifacts

- [sevenwwu.github.io](https://sevenwwu.github.io/)
- [data_curation_readme.md](data_curation_readme.md)
- [curated_dataset.csv](curated_dataset.csv) (as of 11/17/23)
- [Data Science 311 Findings.ipynb](../../Data%20Science%20311%20Findings.ipynb) (as of 11/17/23)
- [surveyoutline.md](surveyoutline.md)
- [survey qr-updated.png](survey%20qr-updated.png)

# Faults
As the survey responses initially appeared insufficient, we spent some time seeking out alternative datasets, which resulted in a delay in our progress. Nevertheless, we have decided to proceed with the survey data we have and are now working to catch up and move forward with our analysis.

Because of this, our project has these shortfalls for Milestone 1:

- Exploratory analysis is not quite at "bulk of ... is done and presentable"

- Evaluation Environment is not "done and presentable" as it has yet to be established

These shortcomings will be resolved by Milestone 2, see [Roadmap](#roadmap).

The search for additional datasets, despite not being used due to the adequacy of survey responses, was a significant part of our initial work. This effort shows our dedication and effort to reinforce our research. The proof of these efforts, even though not used in our project, are detailed below:

[Real Estate Sales in Connecticut 2001-2020](https://catalog.data.gov/dataset/real-estate-sales-2001-2018)
- [Notebook](real_estate.ipynb)

[Common Voice](https://www.kaggle.com/datasets/mozillaorg/common-voice?select=cv-other-train.csv)
- [Notebook](common_voice.ipynb)

# Roadmap

- Team will finish exploring dataset for trends and meaningful correlations for use in the machine learning aspect of the project. 

- Team will establish Machine Learning environment for model training, validation, testing

- Team will explore different Machine Learning models like RandomForestRegression, K-NearestNeighbor, and Logistic Regression on decided features.
