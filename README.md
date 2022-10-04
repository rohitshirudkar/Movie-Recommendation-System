# Movie-Recommendation-System
You might have wondered sometime or at some point that how do platforms like Netflix or AmazonPrime Video are able to recommend us TV shows or movies, what kind of an algorithm do these websites use to recommend us movies. Well as complicated or difficult as it might seem this is simply just a mixture of some machine learning algorithms with some Natural Language Processing.

There are two main techniques used in recommendation system, known as content-based filtering and collaborative filtering

**Content Based Recommendation System:** It uses attributes such as genre, director, description, actors, etc. for movies, to make suggestions for the users. The intuition behind this sort of recommendation system is that if a user liked a particular movie or show, he/she might like a movie or a show similar to it.

**Collaborative Based Recommendation System:** It matches users with same interests and gives recommendations based on their likes. Eg: There are two users Sam and Robin, Sam likes movies A,B,C,D and Robin likes movies C,D. Since movies C,D are common to both Sam and Robin, thus movies A and B would be recommended to Robin. Collaborative filtering does not make use of metadata to give recommendations.

For this project I have used Content Based filtering, as I think using metadata like ‘genres’, ‘actor’ , ‘overview/plot’ can provide us a good deal of insight on understanding users preferences and help recommend movies or TV shows according to this. It helps get a good gauge of users likes/dislikes.


