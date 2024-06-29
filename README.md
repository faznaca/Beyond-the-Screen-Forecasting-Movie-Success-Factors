# BEYOND THE SCREEN: FORECASTING MOVIE SUCCESS FACTORS

## Introduction
Embarking on an exploration of the intricate dynamics within the movie industry, we immerse ourselves in the IMDb 5000 movies dataset to decipher the enigmatic formula of cinematic success. Our mission is clear: to unravel the nuances that distinguish acclaimed films and box office sensations from the crowd. Through a meticulous examination of directors, actors, genres, budgets, and beyond, we endeavor to unveil the underlying patterns driving triumph in the world of cinema. At the heart of our endeavor lies a twofold objective: predicting a movie's IMDb category and discerning its success. Employing advanced machine learning techniques, we meticulously analyze the dataset to unearth the pivotal factors shaping a movie's categorization and performance. These insights hold profound significance for filmmakers, producers, and industry stakeholders, empowering them with the foresight to navigate the ever-evolving landscape of filmmaking.

After exhaustive evaluation of various models, our journey culminates in the selection of Random Forest as the epitome of performance, boasting an impressive accuracy of 0.8094. Its resilience and precision make it the optimal choice for our predictive task, even without extensive hyperparameter tuning.

To democratize access to our insights, we've crafted a user-friendly web application using Streamlit. This intuitive platform enables users to input key features and receive predictions on a movie's IMDb score category—be it Poor, Average, or Good—signifying its potential success. By encapsulating our findings in a practical tool, we aim to equip industry stakeholders with the tools they need to navigate the cinematic landscape with confidence and clarity.

## Problem Statement       
Our main goal is to develop robust models capable of predicting two key aspects of a movie's performance: its IMDb category and whether it succeeds or not. We'll analyze the dataset extensively using machine learning techniques to uncover the factors influencing a movie's categorization and success. These insights will be invaluable for filmmakers, producers, and the movie industry's advancement overall.

## Data Profiling
This dataset provides comprehensive information about movies, capturing various factors that influence a film's commercial success, including directors, actors, critic reviews, and audience reactions. IMDb scores are a key metric for gauging a movie's success. We utilized the IMDb 5000 movie dataset, which contains detailed data for 5043 movies across 28 different attributes. The attributes included are listed below:

### Features of the Dataset
1.	**Color:** Indicates if the movie is black-and-white or colored.
2.	**Director name:** Name of the movie director.
3.	**num_critic_for_reviews:** Number of critics who reviewed the movie.
4.	**Duration:** Duration of the movie in minutes.
5.	**director_facebook_likes:** Number of likes for the director on Facebook.
6.	**actor_3_facebook_likes:** Number of likes for the third lead actor on Facebook.
7.	**actor2_name:** Name of the second lead actor.
8.	**actor_1_facebook_likes:** Number of likes for the lead actor on Facebook.
9.	**Gross:** Gross earnings of the movie in dollars.
10.	**Genres:** Film categorization, such as 'Animation', 'Comedy', 'Romance', 'Horror', 'Sci-Fi', 'Action', 'Family'.
11.	**actor_1_name:** Name of the lead actor.
12.	**Movie title:** Title of the movie.
13.	**num_voted_users:** Number of people who voted for the movie.
14.	**cast_total_facebook_likes:** Total number of Facebook likes for the movie's cast.
15.	**actor_3_name:** Name of the third lead actor.
16.	**facenumber_in_poster:** Number of actors featured in the movie poster.
17.	**Plot keywords:** Keywords describing the movie plot.
18.	**movie_imdb_link:** IMDb link of the movie.
19.	**num_user_for_reviews:** Number of users who reviewed the movie.
20.	**Language:** Language in which the movie is made.
21.	**Country:** Country where the movie was produced.
22.	**Content rating:** Content rating of the movie.
23.	**Budget:** Budget of the movie in dollars.
24.	**Title year:** Year in which the movie was released.
25.	**actor_2_facebook_likes:** Number of Facebook likes for the second lead actor.
26.	**imdb_score:** IMDb score of the movie.
27.	**Aspect ratio:** Aspect ratio in which the movie was made.
28.	**movie_facebook_likes:** Total number of Facebook likes for the movie

## Model Deployment In Streamlit

Deploying a machine learning model in Streamlit is a straightforward process. Streamlit is a Python library that allows you to create interactive web applications for data science and machine learning projects. A Streamlit web application was developed to host the trained machine learning model. The application provides users with a user-friendly interface to input movie features and receive predictions for IMDb score categories. The design emphasizes simplicity and interactivity.

Hosted Website : https://imdbmoviesuccess.streamlit.app/

## References
1. Dataset- https://www.kaggle.com/
2. Website Hosting-https://streamlit.io/
3. https://link.springer.com/chapter/10.1007/978-3-030-47436-1_14
4. https://ieeexplore.ieee.org/
5. https://www.sciencedirect.com/science/article/



