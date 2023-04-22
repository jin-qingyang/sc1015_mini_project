# sc1015 mini project

NTU AY2022/2023 Semester 2 SC1015 Group Project

Our group choose a kaggle dataset about video games and their sales to analyse the important factors affecting the sales of the video games

## Project Summary

### Dataset

Our dataset is on video games sales and contains the name, platform, year of release, genre, publisher of each video game. It also contains the video game’s sales in North America, Europe, Japan, and other regions. It also features scores and ratings from both critics and users, including average critic score, number of critics reviewed, average user score, number of users reviewed, developer, and rating.

### Problem Statement

We want to help developers find out what features of a video game would result in the highest global sales and ratings.

### Machine Learning Models

1. Linear Regression
2. Decision Tree
3. Logistic Regression
4. Support Vector Machine
5. Random Forest

### Results

Overall train and test accuracy was low despite trying various machine learning models. The better performing models where those that could effectively deal with mixed data, like decision trees and random forest. Although some conclusions could be drawn, such as "Games of the genre platform are more likely to also have higher global sales.", these conclusions hold less weight due to the low classification accuracies.

Possible reasons for the poor classifications include:
1. There are other variables not found in this dataset that better explain the distribution of global sales. (e.g. Developer type: AAA, indie etc.)
2. Genres provided are not specific enough to gather sufficient insight. (e.g. "Shooter" is a genre provided, but it can be divided into subcategories like first-person shooter or third-person shooter, which might help us get better results if, for example, there are more global sales for a first-person shooter.)
3. Genres provided do not consider intermingling of genres. (e.g. A "Platformer" often incooperates "Puzzle" elements, but in this dataset, games are only assigned one genre, so this is not considered.)
4. Not enough genres are considered. (e.g. Genres such as single-player and multiplayer are not included in the dataset)



## Links
- [Kaggle Dataset] (https://www.kaggle.com/datasets/ibriiee/video-games-sales-dataset-2022-updated-extra-feat)
- [Video Presentation]



## Team Members

| Name             | Email                  
|------------------|------------------------
| Chong Geng Yang  | gchong016@e.ntu.edu.sg 
| Jin Qingyang     | JINQ0003@e.ntu.edu.sg  
| Li Zhiyuan       | d220009@e.ntu.edu.sg   

## Contibutions

| Part                        | Name                  
|-----------------------------|------------------------
| Data Cleaning               | Geng Yang
|                             | Qingyang
|                             | Zhiyuan
|-----------------------------|------------------------
| Exploratory Data Analysis   | Geng Yang
|                             | Qingyang
|                             | Zhiyuan
|-----------------------------|------------------------
| Machine Learning Models     | Qingyang
|                             | Zhiyuan
|                             |
|-----------------------------|------------------------
| Additional Research         | Geng Yang
|                             | Qingyang                  



