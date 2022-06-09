# UPC-ML-Course-Project
Course Project for Machine Learning Course 2022 at the Politechnical University of Catalunya (UPC). Authors are Alex Martorell and Louis Van Langendonck

## Project Statement
For this study, the 2020 New York City Police Department (NYPD) Stop, Question and Frisk Data Set is used. It can be found at https://www1.nyc.gov/site/nypd/stats/reports-analysis/stopfrisk.page. The data set considers a practice in New York City called "Stop, Question and Frisk". This widely known procedure consists of an officer stopping a person whenever there is a suspicion that a crime is being committed, sometimes followed by an arrest or a frisk (passing the hands over someone in a search for hidden items). According to NYPD regulations, for each stopping action a Police Officer completes, he or she must report it by filling in a UF-250 form. The filled out forms of the year 2020 constitute this data set. 

The goal of this project is to try and predict race based on the different categorical and numerical variables available. The reason behind this choice is two-fold: Firstly, correlations between variables were assessed (as explained in the Project Proposal) and some already insightful results were obtained for some variables in the data set. Secondly, the debate on Race in America has existed since its foundation as a country, and recently has been back in the news again regarding Five-O (Five-O is US-street slang for "Police") brutality claims. There are many studies that have already targeted Police data and found a clear racial bias in some of their actions. This is why it may also be interesting to study further correlations, by looking at how predictive models are able to distinguish the stop and frisk of a Black person, a White person or a person of different origin (i.e. "Black stops" have higher probability than "White stops" at nighttime).

## How to run the project? 
The content of the repository is self containing, meaning that data, source code, etc. is all included. To run through the main steps of the project, navigate to **./src/main/**, where five notebooks can be found. Run these in chronological order (preprocessing -> Feature selection -> Clustering -> Best Models (an overview of the three optimized models) -> final model evaluation). If the structure of the repository is maintained all paths (fe. data path) should be referred to in the notebooks, otherwise the user will have to define manually where to find the datasets, the stored models, etc. 

## Prerequisites
All code is written in Python 3.9.7. Corresponding versions of the regular packages (numpy, pandas, sklearn, ...) are necessary. 
