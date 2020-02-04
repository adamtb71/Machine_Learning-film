# Machine_Learning-film
The objective of this project was to use machine learning techniques for analyzing Movies. We wanted to explore predictive applications explore business decisions movie companies would make. 

From the data we looked at was aggregated critical scores from websites like Metacritic, Rotten Tomatoes and IMDB. We also had financial data like movies' budgets and revenue. And finally, we had a description of the movie plots. 

Going into the project we had 2 objectives. one was to find a connection between critical and financial success. The second was to explore sentiment analysis to see how a movie plot can either predict financial or critical success. 

In the area of predicting Movie reviews With financial success we defined financial success as a ratio of Revenue and the Budget. The intention of this was to equalize films with different revenues and look into simply what was invested in the movies. we created this with the R/B ratio. 

The data was pulled from a Movie database API, which gave us about 3,200 movies to look over. 

The data was changed using a combination of pandas and Excel. There are many instances of outputting CSV files and inputting CSV. this was because certain manipulations were performed in excel. 

For the first analysis, we simply used SKlearn that effectively created a linear regression. And explained the relationship between critical reviews and performance. 

This did yield a positive correlation. So as critical reviews went up, film B/R ratio also went up. However, this was not statistically significant, especially with an R squared at .05-.08 depending upon the critical source. 

Later, we looked at using a sentiment analysis, this case Vader, to examine the plot description and see how well that can predict a movie's financial or critical success. first what Vader. An important note is that sentiment analysis is normally trained to determine positive or negative reviews. However, we wanted to train the system to recognize if there can be for positive or negative reviews.

Overall, we were able to predict if a movie could become a financial or critical success. in the last parts of the code, there is a part where the user can enter in their own plot. 

