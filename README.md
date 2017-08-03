# OkCupid Analysis

The goal of this study is to improve user experience by analyzing and predicting data.
Improved user experience can be achieved through more matches. To get more matches, a better representation of data would be helpful. This could include self-reports. However, an even better method could be acheived through predictions using this data for machine learning.

A benefit of having a machine learning model could be from predicting categories. OkCupid users rely on filtering categories such as age, sex, orientation, education and many more to find matches. However, it is difficult tell if all users are honest or even consistent. With implementation of machine learning algorithmns, we can help both user find matches. We can also use machine learning to predict categories that don't exist yet such as combining like variables to predict introverts, extroverts, and etc.

## OkCupid Analysis Part 1 - Understanding the Variables
Our goal for part 1 is to understand the variables in the OkCupid dataset. Just by listing all of the variables, we can already assume which are more interesting than others. However, let's looking into each just to understand the formats such as: selected word responses, numerical responses, and written responses.

## OkCupid Analysis Part 2 - Cleaning the Data
In part 2, we clean up the data before we process and analyze it. We also focus on extreme responses that deviate away from the average response. We clean up the numbers so we can find averages and make it ready for machine learning. We clean up the essays for the same reason.

## OkCupid Analysis Part 3 - Analyzing the Data
Here, we use the clean dataset produced from part 2. We plot histograms, pie, and bar charts to see interesting relationships. If we see anything worth taking time with, we use it again for machine learning algoritims and predictions.

## OkCupid Analysis Part 4 - Modeling the Data
Our final part of our analysis is focused on modeling the data with the help of Machine Learning. The overall intention here is to be able to predict data to help OkCupid users match more easily. We are going to be focusing on text data. Since we are using text, not numbers, we use classifiers. We have labeled data and are trying to predict categories so we use the Naive Bayes method.
Naive Bayes methods are a set of supervised learning algorithms based on applying Bayes’ theorem with the “naive” assumption of independence between every pair of features.
