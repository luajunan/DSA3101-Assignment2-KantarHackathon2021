# DSA3101 Assignment 2 (Kantar Hackathon)

## Project: Recommending Optimal Basket Through a Media Plan

## Project Description

This is our group's submission for the KANTAR-NUS DACC Data Science Hackathon 2021. Our group achieved the 1st position in this hackathon as well.

Data Science Techniques:
1. Exploratory Data Analysis
2. K-Means Clustering
3. Feature Extraction
4. Feature Engineering
5. Market Basket Analysis
6. Recommender System 
7. Natural Language Processing (NLP)

## Objective of Project

The main objective of the Hackathon is to encourage the population to minimise their spending on packaged foods while maintaining an optimal level of calories consumption based on previous habits. In other words, it is to promote healthier purchasing and consumption habits.

To achieve this, our group’s sub-objectives are as follows:

1)	To identify different consumers segments based on their personal details and overall lifestyle such as spending habits and media consumption

2)	To identify suitable media channels through which we can maximize our campaign’s media outreach

3)	To incentivise and encourage different consumer segments to continually purchase healthier substitutes

4)	To design a mobile application which utilises a recommendation system for the different consumer segments to purchase healthier substitutes

More importantly, our overall plan focuses on a long-term implementation period because we believe the adoption of a healthier lifestyle requires time. Using this approach, the future potential of our strategies will ensure that the effects of these measures are not temporary and truly encourage change in mindset and lifestyle among consumers.

## Using NLP to Optimise Basket

![My First Board (3)](https://user-images.githubusercontent.com/65394783/141642671-c154055b-f51e-4b54-9ded-5c8bdd658511.jpg)

Using this flowchart to better explain our architecture, items in our dataset will be passed into the Bidirectional Encoder Representation from Transformers (BERT) model with the aim of finding semantically similar items. By converting the items into word embeddings, we simplify the problem by calculating the cosine similarity between two words to decide if they are semantically similar.

To give a better understanding of how this works, we plotted out the word embeddings in a 3D space.


https://user-images.githubusercontent.com/65394783/141642777-72533fb3-e6a7-4a3e-a14a-908fb86a1acc.mp4

The main motivation of this method is so that we provide reasonable substitutes for a given food, instead of doing so manually. From this GIF, we can see that the Spaghetti-Rice pair is much closer in the 3D space as compared to the Honey-Sugar pair. Hence, with this interesting characteristic, our architecture is able to provide sensible and healthier options by filtering through this NLP layer and by rewarding/penalising a given food based on their nutrition.


# Team Contributors

1. [Lua Jun An](https://github.com/luajunan) 
2. [Keith Tay Xiang Rui](https://github.com/keith-tay)
3. Tu Zhehao
4. Timothy Wong Hoey Pheen
5. [Ahmad As-Shodiqqul Amin](https://github.com/shodiqqul)
6. [Dione Lim Yee Sze](https://github.com/DioneLim)
7. Kellie Chin Shu Wen
8. Ni Hui Ling
