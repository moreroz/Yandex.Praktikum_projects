# big-city-music
Compare the music preferences of the cities of Springfield and Shelbyville. Real Yandex.Music data to test the hypotheses below and compare user behavior for these two cities.
Contents 
Introduction
Stage 1. Data overview
Conclusions
Stage 2. Data preprocessing
2.1 Header style
2.2 Missing values
2.3 Duplicates
2.4 Conclusions
Stage 3. Testing the hypotheses
3.1 Hypothesis 1: user activity in the two cities
3.2 Hypothesis 2: music preferences on Monday and Friday
3.3 Hypothesis 3: genre preferences in Springfield and Shelbyville
Findings

Introduction 
Whenever we're doing research, we need to formulate hypotheses that we can then test. Sometimes we accept these hypotheses; other times, we reject them. To make the right decisions, a business must be able to understand whether or not it's making the right assumptions.

In this project, we'll compare the music preferences of the cities of Springfield and Shelbyville. We'll study real Yandex.Music data to test the hypotheses below and compare user behavior for these two cities.

Goal:
Test three hypotheses:

User activity differs depending on the day of the week and from city to city.
On Monday mornings, Springfield and Shelbyville residents listen to different genres. This is also true for Friday evenings.
Springfield and Shelbyville listeners have different preferences. In Springfield, they prefer pop, while Shelbyville has more rap fans.
Stages
Data on user behavior is stored in the file /datasets/music_project_en.csv. There is no information about the quality of the data, so you will need to explore it before testing the hypotheses.

First, we'll evaluate the quality of the data and see whether its issues are significant. Then, during data preprocessing, we will try to account for the most critical problems.

Our project will consist of three stages:

Data overview
Data preprocessing
Testing the hypotheses
