# Demo (repo info below)
<img width="800" alt="Movie1" src="https://user-images.githubusercontent.com/108680051/219327716-e58461e6-2bfc-4828-b5cb-3a01b530efa9.png">
<img width="800" alt="Movie2" src="https://user-images.githubusercontent.com/108680051/219327956-f199ee63-2307-4627-8628-a8a7a19adb5e.png">
<img width="800" alt="Movie4" src="https://user-images.githubusercontent.com/108680051/219327977-24a3d977-2e3c-44e7-a54a-b51b2485dd0a.png">


# File Overview 

Project3_Marta_EDA_Final - EDA for tittle basics, akas and title rattings and releatad KPI's.
Rotten - This is the code for the word cloud to be used in the streamlit application.
luisa_p- In this code we also explore the following KPI's: top actor, top actrisses, top writers and directs.
project3_geral - The file for the join tables we will use in the model.
Project3_Recomendation_system - The model
Project3_Streamlit_app - Code for the streamlit application.





### Data Analysis
- Total movies analyzed -> +imbd.sum()
- Years -> imdb from XXXX to YYYY, count of movies x year
- TOP GENRES / CATEGORY -> rotten
- TOP Production Co -> rotten
- TOP Producers -> imdb
- TOP Directors -> imdb
- TOP Actors (female) -> imdb
- TOP Actors (male) -> imdb
- TOP Movies -> imdb
- Genre/category -> wordcloud ->rotten
- TOP movies -> wordlcloud -> rotten


### Application

Before running streamlit:

pip install streamlit-nested-layout

pip install streamlit_option_menu

pip install threadpoolctl==3.1.0


## Movie Recomendation system

- Movie recommendation site 
    - input: movie name,
    - based on start year, title type, weighted average, genre. 


Documentation explaining each column and each table: https://www.imdb.com/interfaces/

Datasets: https://datasets.imdbws.com/ 

Reviews: https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset

Other: https://blogs.gartner.com/martin-kihn/how-to-build-a-recommender-system-in-python/



