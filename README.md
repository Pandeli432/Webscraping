# Webscraping
A look into movie statistics using data acquired via webscrapping

This project contains two files: Movie_scraping.ipynb and Top 1000 Moves.csv
 Movie_scraping.ipynb contains the python code and Top 1000 Moves.csv is the csv file where the data is stored.

The objective of this project was to answer the following four questions: 
1. What years had the most movies ranked in the top 1000 movies?
2. What are the most common run times for the top 1000 movies?
3. What are the top 10 highest grossing films in the top 1000 movies list?
4. What are the 10 least grossing films in the top 1000 movies list?

To complete the task, two websites were used.
The first was 'http://www.rinkworks.com/checklist/list.cgi?u=aquascape&U=taylordw&p=imdbtop1000' which provided a list of the top 1000 movies from imdb and their hyperlinks.
This website was used as I found it incredibly difficult to scrape the movie list via imdb itself. The list was not without flaws and it turned out that 4 movies were 
repeated. The provided movie hyperlinks were then used to search through imdb.

I cannot specify all of the imdb links used, as there were nearly a thousand of them. However, a list of the links is printed in the program and here is 
the link to imdb https://www.imdb.com/. It takes 15min for the function I created to scrape the nearly 1,000 imdb websites.

At the end the answers were answered and the most surprising thing was how few some movies made. I had to check imdb to make sure the data was correct and according
to imdb the data was correct. 
