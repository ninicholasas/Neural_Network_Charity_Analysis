# Neural_Network_Charity_Analysis

## Overview of the Analysis
The goal for this project is to create a bunary classifier that is capable of predicting whetherapplicants will be successful if funded by Alphabet Soup.<br>
The data that we used is a CSV ontaining more than 34,000 organizations that have received funding from Alphabet Soup over the years.<br>
I have used TesorFlow, Scikit-Learn for this analysis.

## Results
* First Attempt
<img width="568" alt="First_Attempt" src="https://user-images.githubusercontent.com/110373282/217586752-d8647b97-2871-42b6-99cd-da5635b598da.png">

I added a hidden layer and changed the epochs to 200.
The Accuaracy score was 0.7281632423400879, slightly higher than original.

* Second Attempt
<img width="598" alt="Second_Attempt" src="https://user-images.githubusercontent.com/110373282/217586771-7c2fe58e-cc3a-43ad-a2e9-dee7ec39ea50.png">

I added another hidden layer to see whether the accuracy will increase or not.
The Accuracy score was 0.7289795875549316, slightly higher that the first attempt, adding the 4th layer seems like it isn't helping as much.

* Third Attempt
<img width="592" alt="Third_Attempt" src="https://user-images.githubusercontent.com/110373282/217586787-8c909a6c-ac43-474a-bf6e-64c829613eb5.png">

Dropped an additional column lowered the epochs to 170.
The Accuracy score was 0.7300291657447815, higher than the previous attempts but wasn't able to reach 75%.

## Summary
Within this challenge, I was not able to achieve the desired accuracy of 75% or more.
I have tried removing different columns, changing epochs and adding layers but there were know significant results.<br>
Using the Tanh or different activation is considered for further analysis.
