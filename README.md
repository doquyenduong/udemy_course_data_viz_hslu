# udemy_course_data_viz_hslu
This is a project to make __a dashboard with Tableau__ for the module "Computer Science for Data Scientists" in the first semester at HSLU. This is my first Tableau project.

## Project description
* You choose the data and task for your visualization project yourself. Your job is to develop a meaningful interactive visualization solving the task defined by you in Tableau (e.g., dashboard). Although there are technical requirements below, focus on the task: What do you want to reveal in the visualization? In order to organize your thoughts, you need to prepare a visualization draft beforehand to the project discussion with the lecturer.
* Your original data set must contain at least 1000 rows and 7 colums (dimensions)
* You must not use Tableau Prep for the data preprocessing but shell preprocessing tools
* You applied at least 3 shell tools to preprocess the data (text editors (vim, nano, etc.), programming languages (python, perl, php, java, r, etc.), and file and directory commands (cd, cp, mv, rm, etc.) are not a shell tool)
* Your final visualization is interactive: you allow interactive filtering and reveal details on demand

## My project topic

Online learning has recently become one of the common options not only for students but also for those who would like to broaden their knowledge and gain new skills in specific domains. Because of the significant benefits such as accessibility and flexibility, and especially after the pandemic, online learning can be the future and likely take the place of land-based learning in a certain way. Over the last decade, numerous online courses have been created. To name but a few, Udemy, Coursera, Lynda, Skillshare, Udacity are the most popular online learning platforms that serve millions of users all over the world.

This analysis report is inspired by Udemy, one of the top-trending online platforms, offering more than 155 000 courses by 56 000 instructors for more than 40 million learners in more than 65 languages up to date (Udemy, 2021). Udemy, founded in May 2010, is an American online learning platform aimed at professional adults and students that offers both free and paid courses. Anybody can create an online class. This is the business model which grants Udemy to have diverse lessons. Students take courses vastly to improve life and job-related skills: some courses generate credit toward technical certifications. Udemy has made a special effort to attract corporate trainers seeking to create coursework for employees of their company.

Using the dataset found on Kaggle  about courses on Udemy, I analyze the performance of online courses and getting insights about users' preferences in terms of course price, level, course duration. This analysis report is carried out by several main steps: data cleaning, data visualization, and interpretation of the findings.

## Research questions

Numerous questions can be initiated from the dataset. However, the project only concentrates on the popularity of Udemy courses from the dataset. Deriving from the motivation, the research questions are formulated as below:     

-	What are the most popular courses and subjects in Udemy?
-	Which factors influence the course popularity within Udemy?

## Data description 
In this project, we look at various courses offered by Udemy on the available data from the publishing year 2011 to 2017. Noticeably, it only covers the first six months of 2017. There are 3,682 observations (rows) and 12 features (columns). Udemy courses are divided into four main subjects (business finance, graphic design, musical instruments, and web design) (Larxel, 2020). 

1.	course_id:	Integer	Course ID
2.	course_title:	String	Course title
3	.url	String:	Course URL
4.	is_paid:	Boolean	Whether the course is free or paid
5.	price:	Integer	Course price
6.	num_subscribers:	Integer	Number of subscribers
7.	num_reviews:	Integer	Number of reviews
8.	num_lectures:	Integer	Number of lectures
9.	level:	Object	Course levels
10.	content_duration:	Float	Duration of the course material
11.	published_timestamp:	String	The date that the course was published
12.	subject:	String	Course subject

## Dashboard
![image](https://user-images.githubusercontent.com/83208743/171133326-0b0388e4-0ab1-4a82-8e8f-88b7d49a3b17.png)


