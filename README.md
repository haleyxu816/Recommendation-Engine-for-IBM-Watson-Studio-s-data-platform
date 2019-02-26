# Recommendation-Engine-for-IBM-Watson-Studio-data-platform

### Table of Contents

1. [Project Motivation](#motivation)
2. [File Descriptions](#files)
3. [Methodology](#use)
4. [Data Source](#source)

## Project Motivation<a name="motivation"></a>

For this project I will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles I think they will like. 


## File Descriptions <a name="files"></a>

1. data :   
   articles_communitie.csv : information about all articles in community, including article id, article title,article summary,article content.
   
   user-item-interactions.csv : information about all interactions between users and articles
   
2. Recommendations_with_IBM.ipynb : Jupyter notebook that includes all the working code
   

## Methodology<a name="use"></a>

### Rank Based Recommendations
To get started in building recommendations, I will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles I might recommend to new users (or anyone depending on what I know about them).  

### User-User Based Collaborative Filtering
In order to build better recommendations for the users of IBM's platform, I would look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. 

### Content Based Recommendations
Using my NLP skills, here might come up with some extremely creative ways to develop a content based recommendation system. 

### Matrix Factorization
Finally, I will complete a machine learning approach to building recommendations. Using the user-item interactions, I will build out a matrix decomposition. Using my decomposition, I will get an idea of how well I can predict new articles an individual might interact with . I will finally discuss which methods you might use moving forward, and how I might test how well your recommendations are working for engaging users.


## Data Source<a name="source"></a>
Must give credit to [IBM Watson Studio](https://dataplatform.cloud.ibm.com/community?context=wdp) for the data.
