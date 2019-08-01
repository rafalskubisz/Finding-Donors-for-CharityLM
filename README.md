# Finding Donors for CharityLM

This project was completed as a part of the course requirements of Udacity's Data Scientist Nanodegree certification.

## Project Overview

CharityML is a fictitious charity organization located in the heart of Silicon Valley that was established to provide financial support for people eager to learn machine learning. After nearly 32,000 letters were sent to people in the community, CharityML determined that every donation they received came from someone that was making more than $50,000 annually. To expand their potential donor base, CharityML has decided to send letters to residents of California, but to only those most likely to donate to the charity. The aim of the project is to help build an algorithm to best identify potential donors and reduce overhead cost of sending mail.

## Project Objective

In this project, I will apply supervised learning techniques and an analytical mind on data collected for the U.S. census to help CharityML (a fictitious charity organization) identify people most likely to donate to their cause. Firstly, I will explore the data to learn how the census data is recorded. Secondly, I will apply a series of transformations and preprocessing techniques to manipulate the data into a workable format. Thirdly, I will evaluate several supervised learners of my choice on the data and consider which is best suited for the solution. As the next step, I will optimize the model that I have selected as an answer to CharityML’s question. Finally, I will explore the chosen model and its predictions under the hood to see just how well it's performing when considering the data it's given.

## Software and libraries used:

- Python
- NumPy
- pandas
- scikit-learn (v0.17)
- Matplotlib

## Data

The modified census dataset consists of approximately 32,000 data points with each datapoint having 13 features. This dataset is a modified version of the dataset published in the paper "Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid", by Ron Kohavi. You may find this paper online, with the original dataset hosted on UCI.

### Features:

- age: Age
- workclass: Working Class (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
- education_level: Level of Education (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
- education-num: Number of educational years completed
- marital-status: Marital status (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
- occupation: Work Occupation (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
- relationship: Relationship Status (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
- race: Race (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
- sex: Sex (Female, Male)
- capital-gain: Monetary Capital Gains
- capital-loss: Monetary Capital Losses
- hours-per-week: Average Hours Per Week Worked
- native-country: Native Country (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)

### Target Variable:
- income: Income Class (<=50K, >50K)
