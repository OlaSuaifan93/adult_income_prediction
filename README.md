# adult_income_prediction
This dataset comes from the U.S. Census Bureau and was donated by Ronny Kohavi and Barry Becker for research and data mining purposes. It is often used to predict whether an individual's annual income exceeds $50,000 based on various demographic and employment features.
Here’s a breakdown of the information:

Title of Database:

The dataset is called "adult."
Sources:

Original owners: The dataset comes from the U.S. Census Bureau.
Donors: Ronny Kohavi and Barry Becker, who were involved in data mining and visualization at Silicon Graphics. Contact: ronnyk@sgi.com.
Date received: 05/19/96.
Past Usage:

Reference: The dataset was used in research by Ron Kohavi, titled "Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid" (1996).
Target Attribute: The goal is to predict if a person's income is greater than or less than $50,000 per year.
Study Results: The dataset has a nice number of records and has been tested with various machine learning algorithms. The results showed error rates from different models, with the best performing model being NBTree (14.10% error rate).
Relevant Information Paragraph:

The dataset was extracted from the 1994 U.S. Census database by Barry Becker, with conditions to clean the data. Records were filtered based on conditions like age greater than 16 and annual income greater than $100.
Number of Instances:

The dataset contains 48,842 instances, split into train (32,561) and test (16,281) subsets. After removing instances with missing values, there are 45,222 instances.
Number of Attributes:

There are 14 attributes in total: 6 continuous (numerical) and 8 nominal (categorical).
Attribute Information:

Continuous attributes: Age, fnlwgt (final weight), education-num, capital-gain, capital-loss, hours-per-week.
Nominal attributes: Workclass, education, marital-status, occupation, relationship, race, sex, native-country.
Class attribute: The target label is either ">50K" or "<=50K", indicating whether an individual's income is greater than $50,000 or not.
Missing Attribute Values:

Approximately 7% of the instances have missing values.
Class Distribution:

The distribution of income classes is imbalanced. Around 23.93% of instances belong to the ">50K" class, while 76.07% belong to the "<=50K" class (the proportion slightly shifts when excluding missing values).
This dataset is useful for machine learning tasks like classification, especially in predicting income based on demographic and employment factors.
