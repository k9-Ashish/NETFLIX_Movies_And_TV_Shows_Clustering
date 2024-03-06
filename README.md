# NETFLIX_Movies_And_TV_Shows_Clustering

## Problem Statement

**This dataset encompasses television shows and movies accessible on Netflix as of 2019. The data originates from Flixable, a third-party search engine dedicated to Netflix content discovery.**

**Back in 2018, an interesting report was published, revealing that the number of TV shows on Netflix had nearly tripled since 2010. Interestingly, during the same time frame, the number of movies available had decreased by more than 2,000 titles, while TV show availability had experienced a threefold increase. It's fascinating to think about what other insights we might uncover from this dataset.**

**If we merge this dataset with data from other sources like IMDB ratings and Rotten Tomatoes scores, we could discover even more interesting findings.**

**In this project, you are required to do**

### Exploring the Data:

* **Digging into the dataset to uncover insights.**

### Global Content Analysis:

* **Figuring out the types of content available in various countries.**

### TV vs. Movies Trend:

* **Checking if Netflix is favoring TV shows over movies lately.**

### Grouping Similar Content:

* **Sorting alike content by comparing text-based characteristics.**

## Attribute Information
**1. Show ID: A special ID for each Movie or TV Show.**

**2. Type: A tag that tells us if it's a Movie or TV Show.**

**3. Title: The name of the Movie or TV Show.**

**4. Director: The person who directed the Movie.**

**5. Cast: The actors in the Movie or Show.**

**6. Country: Where the Movie or Show was made.**

**7. Date Added: When it got added to Netflix.**

**8. Release Year: The year the Movie or Show originally came out.**

**9. Rating: The TV rating for the content.**

**10. Duration: How long it is, either in minutes or seasons.**

**11. Genre: The category it falls into.**

**12. Description: A short summary of the content.**

# Conclusion:

**1. In this dataset there are two types of contents where 30.86% includes TV shows and the remaining 69.14% carries Movies**

**2. The popular streaming platform started gaining traction after 2014. Since then, the amount of content added has been increasing significantly**

**3. The United States produced the highest amount of content followed by India**

**4. The most popular director on Netflix , with the most titles, is Jan Suter followed by Raul Campos**

**5. TOP 3 content categories are International movies , dramas , comedies.**

**6. It seems like words like "Love", "Man", "World", "Story" , "Christmas" are very common in titles. The word "Christmas" ocuured so many time . The reason maybe those movies released on the month of december. Thus by creating a monthly column we can safely conclude, More mumber of movies get released with christmas in it.**

**7. The audience prefers TV-MA(adult)and TV-14(Young Adults) shows more and the least preferred rating shows are Nc-17(kids). Most of the content watched by the audience is TV-MA (Adult),The second is TV-14 (Yound Adults).The conclusion is drawn here is most of the audience is of mature age.**

**8. Utilized text normalization techniques such as lemmatization and text vectorization using TF-IDF to process and represent textual data.**

**9. Applied different clustering models like Kmeans, hierarchical, DBSCAN on data we got the best cluster arrangements**
 
**10. By applying the silhouette score method for n range clusters on dataset we got best score which is 0.3746 for 3 clusters it means content explained well on their own clusters, by using elbow method after k = 3 curve gets linear it means k = 3 is the best cluster.**
