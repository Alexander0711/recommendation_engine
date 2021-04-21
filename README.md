# Project: Recommendation Engine for articles

## Table of Content

- [Project Overview](#overview)
- [Project Software Stack](#stack)
- [Run the Project](#run)
- [File Structure](#files)
- [Software Requirements](#sw_requirements)
- [Conclusion](#conclusion)
- [Links](#links)


<a id='overview'></a>

## 1. Project Overview

1.1 Project Introduction

The aim is to develop a recommendation engine in Python to suggest new articles to a community of users.

In this project I will analyze the interactions that users have with articles on the IBM Watson Studio platform and make recommendations to them about new articles.

In order to determine which articles to show to each user, we will be performing a study of the data available on the IBM Watson Studio platform. 

1.2 Project Steps

1.2.1 Exploratory Data Analysis

Before making recommendations of any kind, we will need to explore the data of this project. We will perform a short EDA. 

1.2.2 Rank Based Recommendations

To build recommendations, we will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users.

1.2.3 User2User Based Collaborative Filtering

In order to build better recommendations for the users of the platform, we will look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. 

1.2.4 Matrix Factorization

Finally, we will perform a machine learning approach to building recommendations. Using the user-item interactions, we will build out a ML model. We will get an idea of how well we can predict new articles an individual might interact with.

1.3 Data for the project 

- user-item-interactions.csv: file contains user interaction
- articles_community.csv: file contains articles description


<a id='stack'></a>

## 2. Project Software Stack

The software stack of this project contains three main parts:



<a id='run'></a>

## 3. Run the Project

xxx

**_Screenshot 2_**

![Screen](images/Screenshot2.png)




<a id='runapp'></a>

### 3.3. Run

xxx
x



<a id='files'></a>

## 4. File Structure

<pre>
.
├── xxx
│   ├── xxx------------------------# xxx
│       ├── xxx------------------# xxx
│       └──xx---------------#xxx
├── xxx
│   ├── 
│   ├── xxx.csv-------# x
│   ├── xxx.csv---------# DAxx
│   └── xxx.py---------------# Px
├── x ---------------------------# Px
├── xxx
│   └── x.pkl----------------# ML MOx
│   └── xx.py-----------# PERx
├──xxx.db----------------# x
│
</pre>


<a id='sw_requirements'></a>

## 5. Software Requirements

The project uses **Python 3.7** and additional libraries: 
- _pandas_
- _numpy_ 
xxxx

<a id='conclusion'></a>

## 6. Conclusion

xxx

<a id='links'></a>

## 7. Links

x

Help: 

<a href="https://stackoverflow.com/questions/41967511/removing-non-english-words-from-corpus" target="_blank">Stopwords</a>



Ideas, Help and Templates: 

xx

This project was completed as part of the Udacity Data Scientist Nanodegree. 
Code templates and data were provided by Udacity. The data was originally sourced by IBM.

xxx
