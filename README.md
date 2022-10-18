# Welcome To My Portfolio!!!
This portfolio contains my personal sports analytics projects. I will practice the skills of Data Preparation, Exploration, Modeling and Visualization using the tools of Python/R Programming, Spreadsheets, and Machine Learning. I will analyze data from www.fbref.com, which is a public open source database for all stats football (soccer) to do my projects, and also analyze data provided from my sports analytics class. 

## Project 2
### Project Description
In Assignment 2 for IS470, we were asked to determine the best kickers in the NFL given the 2022 NFL Big Data Bowl Files. Our Professor gave us flexibility with this assignment. There is no set way to determine which athletes are the best kickers. Therefore, I feel it is very important to specify what describes the best kickers in the NFL to me. Firstly, when I think of kickers, I’m thinking about those athletes who take field goals- not punts or extra points. This is important to note because again, there’s flexibility in your terms for this particular assignment.

Now, in terms of determining which kickers are the best, I used Machine Learning to generate a statistic that I called Expected Field Goals. Given a host of data containing certain metrics, particularly the length of the field goal and the result- making the field goal or missing, which is a binary value (1, 0), I used a Supervised Learning Logistic Regression Classification Model to predict whether a kick would be made from a given distance.

Then, I would use these predicted values and compare them with a kicker’s actual results. If a kicker was expected to make the field goal from a given distance and did make the field goal or was not expected to make a field goal and made the field goal, he gets a point. Oppositely, if a kicker was expected to make a field goal from a given distance and missed in reality, he gets no points. I would store this point in a new variable called efficiency

So, for every data point available in the data set, I would calculate the efficiency and take the average of the efficiency for a given kicker and multiply it by 100. This would equal the rating of the kicker, which is the percentage of times the kicker performed to or above expectations in comparison to my model

Thus, the kickers with the highest ratings are the best kickers in the NFL

## Project 1
### Project Description
* The first project in my portfolio is for the Google Data Analytics Professional Certificate Capstone. 
* In this Capstone, we had the option of using data provided to us in the course and answer a certain problem provided for us in the course, or we could pick our own data based on our interests. 
* As an aspiring football (soccer) analyst, I chose the latter option. In this project, I used data from www.fbref.com to provide a statistical analysis of Manchester United's 21-22 season, which was their worst season in the modern Premier League era. The goal of the project was to analyze the stats of the English Premier League 21-22 to identify the key metrics which influence success and determine the key factors which influence those metrics. 
* Furthermore, based on my findings, I would provide recommendations to Manchester United in order to experience success in the future seasons to come. In this project, I practiced Data Preparation, Exploration, and Visualization with the tools of Spreadsheets and R Programming. 
* To view my project, click the PDF file commited to this repo titled "Project1-ManchesterUnited2122Analysis-GoogleDataAnalyticsProfCertCapstone.pdf". 



