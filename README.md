# Data-Programming-Class

For Assingment 1:

The objective of this assignment was to:
1. Go to https://newsapi.org and create an account and get a key

2. Write a function getNews(source) that accepts the name of a source, queries the NewsAPI, 
and return back a list of URLs with the news stories that appear in that source. 

3.Use the IBM Watson Natural Language Understanding API, and write a function extractEntities(url) that takes as input a URL,
and returns a list of dictionaries, with every dictionary containing the entity name, the URL where the entity appeared, 
the relevance of the entity to the article, and the sentiment about the entity. 

4. Using the getNews(source) function, get the URLs of the news stories that appear in Wall Street Journal.
Using the getNews(source) function, get the URLs of the news stories that appear in New York Times.
Use the extractEntities(url) function to extract the entities that appear in The Wall Street Journal
and The New York Times stories. Load the extracted entities into a Pandas Dataframe. 

For Assignment 2:

The objective of this assignment was to:
1.Identify a web API that returns data. 
Preferably, you want the data to change over time. (To get even more satisfaction, 
select a data source for which historical data are not readily and easily accessible, so that you construct something unique.)

2.Create a database and the corresponding set of tables for storing the data.
You should model the database accurately.

3.Write Python code that connects to the API, fetches the data, and stores the data in the database.
Make sure that your script can run multiple times without causing errors.

For Assignment 4:

The objective of this assignment was to:
We are getting ready for Halloween, and we want to cook some good food. No, good is not good enough.
We want to first the BEST recipe for Heloween. But to find the best recipe, we need data.
After a 1-min Google search, we find the page https://www.allrecipes.com/recipes/189/holidays-and-events/halloween/ 
that contains recipes for Halloween. From a quick look on the webpage, we see that,
for each recipe we have a star rating, and we also have the number of reviews for the recipe.
So, you need to write a crawler that will parse AllRecipes and fetch data for the recipes. 
For this assignment, we will only fetch the data from the recipes from the results page; 
we will not fetch the recipes themselves. We need to fetch the title of the recipe, the URL for the recipe,
the number of reviews, and the average star rating (out of 5 stars).
