# Intro to Machine Learning: Megaline

## Introduction

Today I will be doing a project on creating a model for Megaline's customers to recommend the newer plans to the users who still uses their legacy plans. The purpose of this project is to put the new skills learned about Machine Learning to the test.

Since the pre-processing of the data has been done in the previous chapters, I will go straight to creating the model.

## Data description
Every observation in the dataset contains monthly behavior information about one user. The information given is as follows: 
 * `сalls` — number of calls,
 * `minutes` — total call duration in minutes,
 * `messages` — number of text messages,
 * `mb_used` — Internet traffic used in MB,
 * `is_ultra` — plan for the current month (Ultra - 1, Smart - 0).
