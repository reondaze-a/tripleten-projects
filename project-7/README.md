# Intro to Machine Learning: Megaline
[Link to the Notebook](https://github.com/reondaze-a/tripleten-projects/blob/main/project-7/machine-learning-intro.ipynb)
## Introduction

Today I will be doing a project on creating a model for Megaline's customers to recommend the newer plans to the users who still uses their legacy plans. The purpose of this project is to put the new skills learned about Machine Learning to the test.

Since the pre-processing of the data has been done in the previous chapters, I will go straight to creating the model.

## Goal
The goal for this project is to develop a model with the highest possible accuracy. In this project, the threshold for accuracy is 0.75. I will check the accuracy using the test dataset.  

## Data description
Every observation in the dataset contains monthly behavior information about one user. The information given is as follows: 
 * `сalls` — number of calls,
 * `minutes` — total call duration in minutes,
 * `messages` — number of text messages,
 * `mb_used` — Internet traffic used in MB,
 * `is_ultra` — plan for the current month (Ultra - 1, Smart - 0).

## Librariws
* Pandas
* Scikit-learn
* Numpy
