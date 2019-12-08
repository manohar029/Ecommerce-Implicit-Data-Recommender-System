# Ecommerce-Implicit-Data-Recommender-System
Personalization ML is one of the key drivers of the Ecommerce business in the current scenario. One could leverage the power of Data Science on customer feedback data to come up with personalized recommendations, discount campaigns, marketing etc. 

In this project, you will see how personalized recommendations can be generated from Ecommerce implicit feedback data (views, clicks, time spent viewing, transactions) as opposed to explicit feedback (ratings).

### Why Implicit feedback data?
* The primary issue in using explicit feedback (user ratings) is that it is very sparce (Just be true to yourselves- do you rate every product that you purchase?) whereas implicit feedback can be captured each and every time the user surfs the app.

* The main reason in using implicit feedback data is that you would like a recommendation according to the context of your query.
(Ex. you are looking for a wrist watch in amazon. If you have not bought/rated a wrist watch previously, you would not have any explicit feedback available and the recommendations will be based on cold-start problem. If you are using the implicit feedback from the user, even though he/she doesn't rate the item we'll have information on the taste of the user by the views, clicks, time user spent viewing a watch and even more creative ways. So, as the user keeps viewing different watches, the more confident we can be on the taste of the user and recommend watches accordingly.)

Hence, with plethora of similar products available on an app, the quicker we can assist a user in finding the right product, the better will be the user satisfaction and conversion rate. 

This project is an attempt to implement the ideas mentioned in this paper (https://arxiv.org/pdf/1806.11371.pdf). Do give it a read for better understanding of the approach and also the business impact.

### Dataset
It is actually very difficult to find an open source implicit feedback datasets. I luckily found one here from a previous competition  
RecSys Challenge 2015 (https://2015.recsyschallenge.com/challenge.html). Though the problem statement is the challenge is different, I just used the dataset to build our recommendation system.   
__Note:__ The user information (user_ID) is not provided in this dataset, so I just tweaked this dataset a little to incorporate the user information.

__Note__: The code was implemented in google colab as the dataset is quite huge and I've faced memory issues and slowness on my 8GB ram machine.
