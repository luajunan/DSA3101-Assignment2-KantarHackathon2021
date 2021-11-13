How to run code:

1. For each ipynb file, there is a "Dataset" folder which contains the relevant datasets required to run the colab file.

2. Load all the datasets into the colab and click "Run all" directly.

3. Exception: In "Survey Analysis" -> "Q6 & Q7 Code", the source code is done in R. Ensure that the working directory is set to the "Dataset" directory before running the code.

4. The pip install code chunks for the packages required to run the code should be present in the ipynb file. In the event that it is not present, please pip install the necessary packages required.

# Description

## Clustering code

We attempted K-Means Clustering to segment and profile our customers based on their eating habits in order to better formulate our strategies and media plan.

## EDA

This colab attempts to perform preliminary data analysis on our dataset to better understand certain correlation or relationship between prominent features.

## Survey Analysis

We perform data analysis on the survey to extract key features so as to formulate a media plan that could maximise outreach so that our strategies can achieve a larger impact on our target audience.

## Recommendation System

This consist of the architecture behind how we decided to recommend healthier options to our target audience. In our architecture, we decided to use **Natural Language Processing (BERT)** to filter out the food options that are semantically similar.
