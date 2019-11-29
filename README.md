# Titanic_Survival_Exploration
Machine Learning

## Introduction and Foundations
### Project: Titanic Survival Exploration
In 1912, the ship RMS Titanic struck an iceberg on its maiden voyage and sank, resulting in the deaths of most of its passengers and crew. In this introductory project, we will explore a subset of the RMS Titanic passenger manifest to determine which features best predict whether someone survived or did not survive. To complete this project, you will need to implement several conditional predictions and answer the questions below. 

The whole process of creating a machine learning model on the famous Titanic dataset, which is used by many people all over the world. It provides information on the fate of passengers on the Titanic, summarized according to economic status (class), sex, age and survival.
### RMS Titanic
The RMS Titanic was a British passenger liner that sank in the North Atlantic Ocean in the early morning hours of 15 April 1912, after it collided with an iceberg during its maiden voyage from Southampton to New York City. There were an estimated 2,224 passengers and crew aboard the ship, and more than 1,500 died, making it one of the deadliest commercial peacetime maritime disasters in modern history. The RMS Titanic was the largest ship afloat at the time it entered service and was the second of three Olympic-class ocean liners operated by the White Star Line. The Titanic was built by the Harland and Wolff shipyard in Belfast. Thomas Andrews, her architect, died in the disaster.

* The very same sample of the RMS Titanic data now shows the Survived feature removed from the DataFrame. Note that data (the passenger data) and outcomes (the outcomes of survival) are now paired. That means for any passenger data.loc[i], they have the survival outcome outcomes[i].

### Making Predictions :

#### Think: Out of the first five passengers, if we predict that all of them survived, what would you expect the accuracy of our predictions to be? Predictions have an accuracy of 60.00%.

If we were asked to make a prediction about any passenger aboard the RMS Titanic whom we knew nothing about, then the best prediction we could make would be that they did not survive. This is because we can assume that a majority of the passengers (more than 50%) did not survive the ship sinking.

* Question 1: Using the RMS Titanic data, how accurate would a prediction be that none of the passengers survived?
* Question 2: How accurate would a prediction be that all female passengers survived and the remaining passengers did not survive?
* Question 3: How accurate would a prediction be that all female passengers and all male passengers younger than 10 survived?
* Question 4: Describe the steps you took to implement the final prediction model so that it got an accuracy of at least 80%. What features did you look at? Were certain features more informative than others? Which conditions did you use to split the survival outcomes in the data? How accurate are your predictions?

### Conclusion
After several iterations of exploring and conditioning on the data, you have built a useful algorithm for predicting the survival of each passenger aboard the RMS Titanic. The technique applied in this project is a manual implementation of a simple machine learning model, the decision tree. A decision tree splits a set of data into smaller and smaller groups (called nodes), by one feature at a time. Each time a subset of the data is split, our predictions become more accurate if each of the resulting subgroups are more homogeneous (contain similar labels) than before. The advantage of having a computer do things for us is that it will be more exhaustive and more precise than our manual exploration above. This link provides another introduction into machine learning using a decision tree.
