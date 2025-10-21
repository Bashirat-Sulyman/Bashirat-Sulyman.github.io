---
layout: post
title: "Exploring Movie Ratings For Future Recommendation System"
date: 2025-10-21
image: assets/images/2.JPG
categories: [Data Analysis, Projects]
tags: [Python, Pandas, Data Visualization, Feature Engineering, Recommendation System]
---

When we think of movie recommendations, like the ones on Netflix or IMDb, we rarely stop to think about the data behind them.  
In this project, I explored a movie ratings dataset to discover patterns about how users rate films, what types of movies get the most attention, and how these insights could power smarter recommendation systems.

[You can view the full analysis and code in this Jupyter Notebook](https://bashirat-sulyman.github.io/Movie_Rating_Analysis/)

---

## Understanding the Data

The dataset combines **movie titles**, **genres**, and **user ratings**.  
After merging and cleaning, I engineered **six new features** to be able to discover more insights and perform more analysis:

1. **Release Year** — extracted from the movie title.  
2. **Decade** — grouped movies by their release era.  
3. **Average Rating per User** — measured how generous or strict users are.  
4. **Rating Year** — tracked how movie popularity changes over time.  
5. **Number of Ratings per Movie** — showed how popular a movie is based on its rating count.  
6. **Number of Genres per Movie** — captured how many categories each movie belongs to.

These features helped move from raw data to meaningful insights that reflect real audience behavior.

---

## Exploratory Data Analysis (EDA)

To better understand the dataset, I explored these guiding questions:

1. What do overall movie ratings look like?  
2. How has rating activity changed over time?  
3. Which movies received the most ratings?  
4. How do users differ in their rating patterns?  
5. Does the number of genres affect a movie’s rating?  
6. Which decades had the highest number of releases?

---

## Key Insights

1. **Users generally give high ratings.**
   ![What do overall movie ratings look like? ](assets/images/1.JPG)  
   Most ratings fall between 3.0 and 5.0, showing that users tend to rate only the movies they enjoy.

2. **Rating activity peaked around the year 2000.**
   ![How has rating activity changed over time?](assets/images/2.JPG)  
   There was a dramatic surge in ratings, followed by a decline and some fluctuations in later years.

3. **Classic movies dominate the dataset.**
   ![Which movies received the most ratings?](assets/images/3.JPG)  
   Movies with the most ratings are classics from the 1990s, showing that rating volume is driven more by long-term popularity than by recent they are.

4. **Users rate movies in similar ways.**
   ![How do users differ in their rating patterns? ](assets/images/4.JPG)
    
   Most users rate movies similarly and tend to give high scores. Very few users give low ratings, so there aren’t many strict raters.

6. **Genre count doesn’t affect ratings much.**
   ![Does the number of genres affect a movie’s rating?](assets/images/5.JPG)  
   Whether a movie has one or several genres, it doesn’t significantly influence how it’s rated.

7. **Most rating activity focuses on older films.**
   ![Which decades had the highest number of releases?](assets/images/6.JPG)  
   The vast majority of rating activity focuses on films released in the 1990s and 2000s. It reinforces the lasting appeal of classic cinema.

---

## What These Mean for Future Recommendation Systems
These findings give a clearer picture of how users interact with movies and ratings and that understanding is key for designing smarter recommendations. These insights discovered can **guide how a recommendation system is built** in the following ways:

**High ratings overall:** Since most users rate movies positively, it means the system shouldn’t just rely on rating scores alone. Instead, it should learn to recognize which users are genuinely selective and which ones tend to give everything a high mark.

**Consider time trends:** The fact that ratings peaked around the year 2000 and dropped afterward suggests that people’s engagement changes with time. A good system could use this to track trends, maybe recommend older classics during throwback periods or highlight currently popular releases.

**Popular classics dominate:** It’s clear that older, well-loved movies attract more ratings. This means a recommendation system needs to find a balance between recommending popular favorites and helping users discover hidden gems they might not know about.

**Users rate generously and similarly:** Because people don’t differ much in how they rate; a model might need to look beyond just numbers. For example, combining rating data with user behavior (like watch history or genres liked) can help create better personalized recommendations.

**Genre count doesn’t affect rating:** The number of genres doesn’t seem to make a movie better or worse in people’s eyes. This suggests that the model should pay more attention to what genres are combined, not how many.

**Ratings mostly focus on 1990s–2000s films:** Since most data points come from that era, recommendations could easily favor older movies. To stay relevant, future systems should make sure new releases get enough visibility too.


Together, these lessons can make recommendations more *personal, diverse, and time-aware.*

---

## What I Learnt

This project taught me how **feature engineering** turns data into insight.  
By creating features like *decade*, *rating year*, and *average rating per user*, I moved beyond descriptive statistics into patterns that could actually influence machine learning or product design.

---


Would you like to explore this yourself?  
Check out the full project on [GitHub](https://github.com/Bashirat-Sulyman/Movie_Rating_Analysis)
