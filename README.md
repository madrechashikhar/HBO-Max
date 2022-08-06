# HBO-Max
HBO Max Capstone Project - University of Chicago

## The Current Situation (Opportunity):
The problem that HBO Max faces is that as consumers become more selective - not just about what they watch, but what services they watch content on - if a platform does not give them the best experience, then they may leave it. A significant part of a user's experience is the content that they are recommended on the platform. If the recommended content is not relevant, subscribers may not have a good user experience.

## Goals of Analysis 

> “We will build a scalable model to generate a list of top "N" relevant movies (based on predicted ratings) for HBO Max's subscribers by extracting richer meta features from historical explicit feedbacks (ratings), user-defined movie tags and other features. The unit of analysis will be a customer.” 

1. Develop a recommendation engine for the HBO Max streaming platform by using the 25M ratings dataset collected by GroupLens research from the MovieLens website. A supervised approach, based on explicit feedback (ratings) provided by users along with user-defined movie tags and other publicly available data, will be used to generate recommendations for each user. 

2. Understand consumer preferences, regarding recommendations provided by various streaming platforms (such as Netflix, Disney, Prime Video, etc), through a survey to come up with novel features to explain user tastes and intention and build them into inputs for the model. 

3. Extract richer meta-features through clustering, encoding, and embedding textual and categorical features such as tags, genres, subject matter, etc., into a lower dimension numerical vector to improve performance and scalability of the model. 

4. Test multiple models covering matrix factorization, K-Means clustering, and deep Neural Networks and evaluate the model performance using recall, precision, and HR@10 scores. 

5. Generate a predicted rating for every movie or TV show not yet seen by the user. 

6. Produce a list of top 10 movies or TV shows which should be recommended to users based on their preferences, past rating history, and predicted ratings. 

7. Create a robust model to address the cold-start problem and be able to generate relevant recommendations for users new to the HBO Max platform. 
