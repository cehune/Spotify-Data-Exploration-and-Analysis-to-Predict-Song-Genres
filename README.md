# Spotify-Data-Exploration-and-Predictions-with-Python

***Predicting Song Genres Using Computerized Sound Metrics***

Coming from a musical background, I was taught about the qualities that dictate certain styles, especially as time progressed. These were more niche qualities, such as the themes, decorations, ideas, and technical aspects engraved into distinct styles. Regardless, I still believe that the more general factors regarding the sound is ample. A human likely wouldn't guess the genre based on it's 'energy', while a computer might be able to. That's what I'm searching to analyze in this project. I want to use technology to understand music at a greater level, and how different factors, that humans cannot easily recognize, dictate and separate certain genres. 

In the regular dataset, I was able to achieve a ROC AUC Score of 0.714. In a modified Dataset, where I picked the six most distinct genres, I achieved a ROC AUC Score of 0.915.

I'm using the *Dataset of songs in Spotify* from Kaggle to analyze Spotify songs based on a variety of factors, including, "loudness", "danceability", and more. It is a container of 40,000 songs. You can find it here.

https://www.kaggle.com/datasets/mrmorj/dataset-of-songs-in-spotify?resource=download

The goal is to perform exploratory analysis first, then move into Machine Learning Techniques including Adaptive Boosting and Hyperparameter Tuning. I'd like to end the project with a prediction model that estimates the genre of songs by using the other columns in the data set. 

I will be using the following Technologies:
- Numpy (calculations)
- Pandas (data manipulation)
- Seaborn (data visualization)
- Scikit Learn (machine learning classification, hyper parameter tuning, boosting)


**Example Graphs**

During exploratory analysis, I found a high variance within the acousticness column in particular. In graphing it, I found that genres were highly distinct in their acousticness level. 

![image](https://user-images.githubusercontent.com/71574223/183154632-7c0cd139-8faf-42a9-8f34-c3c7d65ef8f7.png)

I was curious about the relation of energy and danceability, though I found there isn't a clear positive relation.

![image](https://user-images.githubusercontent.com/71574223/183154765-321b1b52-1511-4f41-bc41-be35efcb491b.png)



