# ML_Cheat_Sheet
A Machine-Learning and Interview Questions "cheat sheet" to prepare for data science and data analytics job interviews. 

The file contains questions and answers from sources such as https://www.springboard.com/blog/data-science/machine-learning-interview-questions/. 

## Algorithms and Theory

____________________
### What is the difference between supervised and unsupervised machine learning?

Supervised learning requires training pre-categorized (labeled) data. For example, in order to do classification (a supervised learning task), you’ll need to first label the data you’ll use to train the model to classify data into your labeled groups. This then allows us to make predictions/predictive models. Classification and regression fall into this category. 

Unsupervised learning, in contrast, does not require labeling data explicitly, but rather deals with clustering data or the creation of an indeterminate number of hypothetical "profiles" that are adjustable depending on the data that's input. 

In essence, supervised learning has a target variable that serves as the basis for prediction of either a number or a category, whereas unsupervised learning has no predetermined targets. 

____________________
### What is the difference between Type I and Type II errors?

Type I error is a false positive, while Type II error is a false negative. 

One way to think about this is to think of Type I error as telling a cisgendered man he is pregnant, while Type II error means you tell a pregnant woman she isn’t carrying a baby.

____________________
### What is deep learning, and how does it contrast with other ML algorithms?

Deep learning is a subset of machine learning that is concerned with neural networks. In that sense, deep learning represents an unsupervised learning algorithm that learns representations of data through the use of neural nets.

____________________
### When should you choose classification over regression?

Classification produces discrete values and dataset to strict categories, while regression gives you continuous results that allow you to better distinguish differences between individual points. You would use classification over regression if you wanted your results to reflect the belongingness of data points in your dataset to certain explicit categories (ex: If you wanted to know whether a name was male or female rather than just how correlated they were with male and female names.)



## Programming Skills

____________________
### How do you handle missing or corrupted data in a dataset? 

You could find missing/corrupted data in a dataset and either drop those rows or columns, or decide to replace them with another value.

In Pandas, there are two very useful methods: isnull() and dropna() that will help you find columns of data with missing or corrupted data and drop those values. If you want to fill the invalid values with a placeholder value (for example, 0), you could use the fillna() method.

____________________
### Which data visualization libraries do you use? 

My personal preferences are for Python's seaborn and matplotlib, which are currently where I have most experience. 

____________________
### Given two strings, A and B, of the same length n, find whether it is possible to cut both strings at a common point such that the first part of A and the second part of B form a palindrome.

There are multiple ways to check for palindromes—one way of doing so if you’re using a programming language such as Python is to reverse the string and check to see if it still equals the original string, for example. The thing to look out for here is the category of questions you can expect, which will be akin to software engineering questions that drill down to your knowledge of algorithms and data structures. (Practice this and similar algorithms in Python). 

____________________
### How are primary and foreign keys related in SQL? 

Foreign keys allow you to match up and join tables together on the primary key of the corresponding table. 

____________________
### What are the data types supported by JSON?

There are six basic JSON datatypes you can manipulate: strings, numbers, objects, arrays, booleans, and null values. 

____________________
### 

## General interest in machine learning

____________________
### Where do you usually source datasets?

Machine learning interview questions like these try to get at the heart of your machine learning interest. Somebody who is truly passionate about machine learning will have gone off and done side projects on their own, and have a good idea of what great datasets are out there. If you’re missing any, check out Quandl for economic and financial data, and Kaggle’s Datasets collection for another great list.

## Company/Industry-Specific Questions

____________________
### What do you think is the most valuable data in our business? 

This question or questions like it really try to test you on two dimensions. The first is your knowledge of the business and the industry itself, as well as your understanding of the business model. The second is whether you can pick how correlated data is to business outcomes in general, and then how you apply that thinking to your context about the company. You’ll want to research the business model and ask good questions to your recruiter—and start thinking about what business problems they probably want to solve most with their data. 