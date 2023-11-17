# **Title:** Final Project Curated Data
## **Author:** Seven Lewis
## **Dataset name:** BoardGameStatsWWU
## **Dataset description:** 
Dataset provides survey responses from WWU students and faculty regarding their demographics and their relationship with board games. 

Demographic info includes survey responses for:
- Student/Faculty Member Status
- Gender Identity
- Age
- Race
- Employment Status
- Corrective Vision
- Religiosity
- Area of Study

Board Game info includes survey responses for:
- Enjoyment of Board Games
- \# of Board Games Owned
- Frequency of Board Game Play
- Style of Player
- Desirable Gameplay Elements
- Enjoyed Board Games
- Scale Rating of Chess
- Desirable Board Game Genres

## **Data provenance:**
Data was collected by walking around campus asking students to fill out the survey. The survey is hosted on Microsoft Forms and is of our own creation.

The question and answer outline can be found [here](surveyoutline.md).

## **Intended usage:**
This data should be used to identify relationships between the demographics of WWU students and specific board game related answers. 

This will hopefully provide interesting incite to trends between the two and perhaps indicate biases within the board gaming community. Additionally, machine learning could be applied to this dataset to predict how many board games someone owns, or how invested they are likely to be in board games. 

## **Data curation:**
The steps for data curation are outlined below:
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

## **Data faults:**
Like all surveys, only those who are willing to fill them out become part of the data set. This is an inherit bias of this form of data collection. Ideally, one being interested in board games is completely independent of one being interested in surveys (allowing for perfect random sampling), but this is unlikely. Additionally, our set of people is confined to those we encountered on campus, which hopefully is a random distribution of WWU, but again, unlikely to be perfect. 

The survey questions themselves are also a source of bias. They could have been asked with bias, causing people to swayed when they answer (another fault of surveys). 

## **Acknowledgements:**
Data survey was primarily written by Seven. Data survey was primarily handed out by Seven. 