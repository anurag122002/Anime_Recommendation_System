# Anime_Recommendation_System: Project Overview 

This is a project which is not very technical neither it is hard to implement and the code structure is pretty simple too. Its no doubt a begginer level project. However, anime is one of the closest things to my heart. While in loneliness it kept me company, while in failure it gave me strength to get back up, Yes, I might sound a bit childish but one thing I can say for certain that there is no show, no film, no series ever made that surpases anime in terms of very peculiar emotions. The emotions that a man faces alone, the will to never giving up, being obssesed with dreams and no matter what the situation or anyone else says, always being true to one's dream and goals . The manliness showcased by every character(Baki, Guts, Ohma Tokita and many other), the wisdom. If I don't stop there might be a million things I could write down in aspects of anime but I think its enough as its a data science project not an open community.

After watching many animes I used to wonder, if I had to suggest one to a someone then what anime should I suggest them and even for myself. I ask this question that if I like this anime then based on it what other animes should I watch. Therefore with this motivation I made this little anime recommendation project.

## Code and Resources Used:-

- **Python Version**: 3.10.13
- **Packages**: numpy, pandas, matplotlib, seaborn, plotly, wordcloud, sklearn
- **Dataset**: https://www.kaggle.com/datasets/vishalmane10/anime-dataset-2022


## EDA

Most of the visualizations were made using the plotly library. I was experimenting and learning to use it. Therefore the github repo does not showcase those files.


![image](https://github.com/anurag122002/Anime_Recommendation_System/assets/111629651/c19b6d81-900a-4e2b-84a9-b125f1ea3260)

![image](https://github.com/anurag122002/Anime_Recommendation_System/assets/111629651/9bf11e23-34db-4bb5-bd59-ea5d0eb8e4c4)


## Content Based Recommender System
A content-based recommender system is a recommendation algorithm that suggests items to users based on the characteristics and features of those items, as well as the user's historical preferences. It analyzes the content or attributes of items and learns the user's preferences by matching these attributes with the user's past interactions or explicit preferences. For example, in a movie recommendation system, it might consider factors like genre, director, actors, and user ratings. Content-based systems are well-suited for suggesting items that are similar in content to what the user has liked in the past. They don't rely on collaborative filtering or user behavior patterns, making them useful in scenarios with sparse user data or when privacy is a concern.

For this project I focused making recommendations based only on the plot description. The users who had liked animes based on a peculiar genre might be interested in anime based on somewhat alike genre description.

- Used Tf-IDF Vectorizer to convert the words in the description into vectors.
- Calculated the cosine similarity and based on that made a function that recommends alike animnes.




