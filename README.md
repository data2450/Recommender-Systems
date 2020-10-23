# Recommender-Systems
The purpose of a recommender system is to suggest users something based on their interest or usage history. So next time Amazon suggests you a product, or Netflix recommends you a tv show or medium display a great post on your feed, understand that there is a recommendation system working under the hood.

It turns out that there are (mostly) three ways to build a recommendation engine:

1.Popularity based recommendation engine

2.Content based recommendation engine

3.Collaborative filtering based recommendation engine

**Popularity based recommendation engine:**
Perhaps, this is the simplest kind of recommendation engine that you will come across. The trending list you see in YouTube or Netflix is based on this algorithm. It keeps a track of view counts for each movie/video and then lists movies based on views in descending order(highest view count to lowest view count). Pretty simple but, effective. Right?

**Content based recommendation engine:**
This type of recommendation systems, takes in a movie that a user currently likes as input. Then it analyzes the contents (storyline, genre, cast, director etc.) of the movie to find out other movies which have similar content. Then it ranks similar movies according to their similarity scores and recommends the most relevant movies to the user.

**Collaborative filtering based recommendation engine:**

This algorithm at first tries to find similar users based on their activities and preferences (for example, both the users watch same type of movies or movies directed by the same director). Now, between these users(say, A and B) if user A has seen a movie that user B has not seen yet, then that movie gets recommended to user B and vice-versa. In other words, the recommendations get filtered based on the collaboration between similar user’s preferences (thus, the name “Collaborative Filtering”). One typical application of this algorithm can be seen in the Amazon e-commerce platform, where you get to see the “Customers who viewed this item also viewed” and “Customers who bought this item also bought” list.

in the 1st movie recommentation system we partially used Content based recommendation engine. we used the similarity between the movies based on their ratings, n.o of rating ,and avearage value of the rating and find movies which is mostly coorelated to the popular movie

