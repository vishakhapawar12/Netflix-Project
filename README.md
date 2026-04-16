# Netflix-Project

<img width="1920" height="1077" alt="image" src="https://github.com/user-attachments/assets/d4cfb7f3-8a81-46da-a7bf-9ec7f303297a" />

## Business context

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Initially i have start with understanding the dataset, then i clean the data to make analysis ready.

Explore the data and understand the behaviour of the same.

Then i have prepare the dataset for creating clusters by various parameters wherein i can remove stop words, white spaces numbers etc. so that i can get important words and based on that i shall form clusters.

Later i have used the silhouette method and k-means elbow method to find optimal number of clusters and built recommender system by cosine similarity and recommended top ten movies.

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

## Dataset:

Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

In this project, required to do:

Exploratory Data Analysis.

Understanding what type content is available in different countries.

Is Netflix has increasingly focusing on TV rather than movies in recent years.

Clustering similar content by matching text-based features.

<img width="485" height="579" alt="image" src="https://github.com/user-attachments/assets/63723f43-4fbe-480f-b919-652d7decfc14" />


## Conclusion:

The objective of the project was to cluster TV shows and movies based on their similarities and differences, with the ultimate goal of creating a content-based recommender system that recommends 10 shows to users based on their viewing history. Some key points from the project include:

* Exploring the dataset consist of 7787 records and 12 attributes, with a focus on missing value imputation and exploratory data analysis (EDA).

* The analysis revealed that Netflix has a greater number of movies than TV shows, with a rapidly growing collection of shows from the United States.

* Collected and processed Netflix movie and TV show data focusing on attributes such as duration, release year, and content type for meaningful insights.

* Performed exploratory data analysis (EDA) using Pandas and Matplotlib to uncover trends in audience preferences, streaming durations, and content popularity.

* Developed a cosine similarity-based recommendation system leveraging clustering insights to suggest similar content and improve recommendation accuracy.

* Achieved actionable insights into content segmentation and audience preferences,enabling optimization of content strategies and personalized recommendations to enhance user satisfaction and engagement.
