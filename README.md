# Welcome To My Portfolio!!!
This portfolio contains my personal sports analytics projects. I will practice the skills of Data Preparation, Exploration, Modeling and Visualization using the tools of Python/R Programming, Spreadsheets, and Machine Learning. 

## Project 4
### Project Description
My submission for the 2023 NFL Big Data Bowl. Code found on Kaggle: https://www.kaggle.com/code/jt2002/bigdatabowl2023joshuathomas

The 2023 Big Data Bowl is focused on everything O-Lineman. In my project, I wanted to develop a rating system for each specific O-Lineman position. In other words, who are the best O-Lineman in the league?

To me, an O-Lineman is good and doing their job if they prevent their respective QB from experiencing ‘pressure’. I’ve defined ‘pressure_allowed’ as the sum of sacks allowed, hits allowed, and hurrys allowed that an O-lineman is attributed to be responsible for.

Thus, ‘total_pressure_allowed’ can be defined as the sum of ‘total sacks allowed’ + ‘total hits allowed’ + ‘total hurrys allowed’.

So, for each O-Lineman available in the dataset, I’m going to calculate their total_pressure_allowed. Then, using Supervised Learning Linear Regression Machine Learning, I’m going to calculate their ‘expectedTotalPressureAllowed’, which is the predicted total_pressure_allowed for an O-Lineman. Then using the formula:

100 - ((actual_total_pressure_allowed - expected_total_pressure_allowed)/expected_total_pressure_allowed) * 100)

I can develop a rating for each O-Lineman and then rank who the best O-Lineman are in each respective O-Lineman position.

NFL teams can use this rating system to determine undervalued players and make reasonable trade or player acquisitions. Additionally, NFL teams can use my Expected Total Pressure Allowed Model to evaluate their current O-Lineman and see if they are meeting expectations

## Project 3
### Project Description
In my CS403 Data Science class, we were asked to scrape API data and do statistical analysis and machine learning. Using the API-Football API found on RapidAPI, I gathered Premier League data from the 2012-2021 seasons to try and answer the following questions:

1) Question 1: What is the confidence interval at the 95% level for the mean number of goals from the years 2012-2016 and 2017-2021?

2) Question 2: Predict the Goal Difference for a Team in the Premier League using Data from 2012-2021 using Linear Regression

3) Question 3: Predict Whether the Number of Wins for a Team in the Premier League is Greater than the Mean Number of Wins from 2012-2021 using Data from 2012-2021 using Logistic Regression Classification

In this project, I practiced building Linear Regression and Logistic Regression Classification Supervised Learning Machine Learning and I practiced scraping API data and usinng get requests for API endpoints. 

## Project 2
### Project Description
Code and Project is on my RPubs Account. Click this link: https://rpubs.com/jathomas2/957845 <br><br>
In Assignment 2 for IS470, we were asked to determine the best kickers in the NFL given the 2022 NFL Big Data Bowl Files. My Professor gave us flexibility with this assignment. There is no set way to determine which athletes are the best kickers. Therefore, I feel it is very important to specify what describes the best kickers in the NFL to me. Firstly, when I think of kickers, I’m thinking about those athletes who take field goals- not punts or extra points. This is important to note because again, there’s flexibility in your terms for this particular assignment.

Now, in terms of determining which kickers are the best, I used Machine Learning to generate a statistic that I called Expected Field Goals. Given a host of data containing certain metrics, particularly the length of the field goal and the result- making the field goal or missing, which is a binary value (1, 0), I used a Supervised Learning Logistic Regression Classification Model to predict whether a kick would be made from a given distance.

Then, I would use these predicted values and compare them with a kicker’s actual results. If a kicker was expected to make the field goal from a given distance and did make the field goal or was not expected to make a field goal and made the field goal, he gets a point. Oppositely, if a kicker was expected to make a field goal from a given distance and missed in reality, he gets no points. I would store this point in a new variable called efficiency

So, for every data point available in the data set, I would calculate the efficiency and take the average of the efficiency for a given kicker and multiply it by 100. This would equal the rating of the kicker, which is the percentage of times the kicker performed to or above expectations in comparison to my model

Thus, the kickers with the highest ratings are the best kickers in the NFL

## Project 1
### Project Description
If there is one sport that I've loved my whole life, it's football (soccer). If there's one competition that has truly resonated with me, it's the
English Premier League. As a life long Manchester United fan, I've always been fascinated with the constant competition, the vibrant
atmospheres, and the wonderful play of the English game. As an aspiring Data Scientist who is getting his feet wet with Machine Learning, I
thought there would be no better way to get acquainted with Supervised Learning than using Premier League data itself. Thus, in my first
Machine Learning Model ever, I'm going to build a Linear Regression Model which can predict with decent accuracy the final wins of a
Premier League Team.




