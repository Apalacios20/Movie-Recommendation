# Movie Recommendation

## Members: 
Anthony Palacios, Osamu Adler, Sergio Basurto, and Michael Diaz 

## Purpose: 
Our project focuses on creating a movie recommendation tool using Machine-Learning (ML) techniques to optimize recommendations to users based on preferered interests, likes, and genres. 

With the plethora of streaming services that exist such as AmazonPrime, HBOMax, Hulu, and of course Netflix, the overwhelming amount of titles can lead to users of these platforms often choosing a movie based on that plaatform's recommendations.  However, those platforms can only base their recommendations on what users have previosuly consumed. With users having many different interests and with different movies exisitng solely on certain platforms, this archaic habit creates an oversight with many great movies and recommendations being left out. Our ML tool looks to fix that pain point by allowing users to get their base recommendations from over 1 million titles based on preferences according to User_id, Movie_id, and title ratings.

## Few things to know about our model:
We built a movie recommendation system using collaborative filtering by implementing the K-Nearest Neighbors algorithm.

### What is collaborative filtering? <br>
This filtering method is based on collecting and analyzing information on user’s behaviors, their activities or preferences, and predicting what they will like based on the similarity with other users. A key advantage of the collaborative filtering approach is that it does not rely on machine analyzable content and thus it is capable of accurately recommending complex items such as movies without requiring an “understanding” of the item itself.  The model does not learn from the demographics of users, instead its solely based on the ratings of similar titles from different users.

### When a user visits the homepage, the system should recommend movies based on both: <br>
•	Similarity to movies the user has liked in the past <br>
•	 Movies that similar users liked

## Sources:
https://grouplens.org/datasets/movielens/


## Requirements:
Python, Tableau, SQL, Google Co-lab, Jupyter Notebooks, AWS

## Dependencies: 

-pandas

-scikitlearn

-numpy

-scipy

-matplotlib
  
## Work Splits:

Web Scrape & Data Preparation- Anthony

ML Process- Anthony

Deployment- Osa

Tableau- Sergio

SQL- Michael
 
## Algorithm:
K-Nearest Neighbors
