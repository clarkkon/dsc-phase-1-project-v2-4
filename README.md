# Top Films and Genres from 2010 to the Present

## Overview and Business Understanding

My project aims to discover the top films, studios, and genres to inform best practice for our new movie studio. __[Here](https://docs.google.com/presentation/d/1_JF67-Pt34Av5e8E7B1tme76G3Ws0CBju3ZH-Sa_wMQ/edit?usp=sharing)__ is the link to my presentation.
Questions: How can our new studio be successful?  What are the ways that current studios have been successful and why? Who can we look to for business models?  What kinds of films should we be creating?  How has the pandemic changed viewers' interests?

## Data Source and Data Description

This data comes from __[Box Office Mojo](www.boxofficemojo.com)__ and the __[Internet Movie Database](www.imdb.com)__ (a.k.a. IMDB). 

The primary columns I used from these databases to determine movie success were

- the domestic gross
- the foreign gross
- the number of review ratings
- the average rating

Taking these variables into consideration, I investigated the top film titles, studios, and film genres. 

The most relevant, success-related columns from Box Office Mojo were  domestic gross and foregin gross amounts. I created another column for the total gross amount for each film, and adjusted those amounts for inflation. 

I created the following visualizations from this data:
![Top Grossing Films](https://user-images.githubusercontent.com/98120389/185688874-2cf1e845-e8c1-4e8a-a157-f9b36accf92e.png)

![Top Grossing Studios](https://user-images.githubusercontent.com/98120389/185688883-b77c49d3-ddad-4986-b8c0-bcfb6081d961.png)

The most relevant, success-related columns from IMDB were the average ratings and the number of votes for said ratings.  I took the top 25% based on each of those columns. I then value counted the genres in this top 25% to determine the top rated genres. 

I created the following visualizations from this data. 
![Top Rated Films](https://user-images.githubusercontent.com/98120389/185688906-8db4b03b-fe86-4c0a-b1ba-5c3672044b7d.png)

![Top Rated Solo Genres](https://user-images.githubusercontent.com/98120389/185688986-af607b5d-ef42-4ad4-ad76-934ff1b1ae0a.png)

![Top Rated MultiGenre Films](https://user-images.githubusercontent.com/98120389/185688914-b3694f1b-654c-49f4-bb80-e25220d1bd6e.png)

![Top Rated Solo Genres Post Pandemic](https://user-images.githubusercontent.com/98120389/185689006-242ee8b5-46ad-4ab1-a917-fe8d7c8702ac.png)

![Top Rated Multigenres Post Pandemic](https://user-images.githubusercontent.com/98120389/185688936-c6fadb6d-79d7-4e98-8d16-30aa3222659e.png)

# Conclusion

Utilizing the variables of total gross, number of reviews, and ratings, I determined the following:

- the highest grossing films (adjusting for inflation)
- the highest grossing studios (adjusting for inflation)
- the highest rated films
- the highest rated genres
- the highest rated genres since the pandemic began

Three Recommendations:

1. The highest grossing films have highest potential appeal for customers and most of them are part of a franchise: Marvel, Harry Potter, Star Wars, Jurassic Park, Transformers, Incredibles, Toy Story, Minions.  These films all are or have sequels, or a part of a franchise with multiple films capitalizing on a created universe.  These are the kinds of films that will bring in the highest dollars. 

2. The highest grossing studios have the best business models that should inform our practice for our own studio. The business strategies of these studios should be carefully scrutinized to determine and emulate their methods for success. 

3. The highest rated films and genres generate the most interest from viewers. These are the kinds of films we should consider making, and we may lean into the post-pandemic information a little more heavily to inform studio choices, as they may be the most relevant to success today. The top genres overall were dramas, documentaries, comedies, action movies, and biographies. Post pandemic, the top genres were dramas, action movies, documentaries, and thrillers.  We should consider creating movies within these genre parameters if we want to generate interest and increase our liklihood of achieving high ratings. 


Navigating the repository:

Data can be found in zippedData folder

awesome.gif is for funsies

movie_data_erd.jpeg is map of the database from IMDB

student.ipynb contains the coding and markup

presentation.pdf is Google Slides presentation of information


