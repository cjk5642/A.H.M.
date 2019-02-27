This file contains the career statistics from Nolan Arenado, Bryce Harper, and Manny Machado since 2013.
I wanted to see who was better amongst the three, since all three are looking to sign major deals currently. 

### Loading in the Data
I first read in each .csv file of each player from baseball-reference.com. Their function above each table to convert to .csv is extremely
  helpful.
Next, I deleted columns I did not need initially. 
Lastly, since each file did not come with names, I had to create a column for when future merging may be necessary.

### Joining the Data
Now I merge all three dataframes into one using pandas' useful pd.concat function.
To give the new dataframe, total, a nice look, I called .groupby on it to order the frame in a "nice" way.
Finally, I removed even more columns that were deemed unnecessary for this analytical job; to which I displayed such chart.

### Plotting the Data
This part took me the longest to do due to the fact that I wanted the plot to be perfect. 
I was unsure which plot would be best, so more brainstorming needed to take place.
At the end, I came to the conclusion I needed the bar graph. 
The next part I needed to do was obtain the data for each column (BA, OPB, SLG, OPS) for each player (Arenado, Harper, Machado). This part
  was extremely tedious due to the exact data I needed to take. 
Next, I needed to obtain each value for each person and produce a plot through iterations of a list of years.
The rest was technical choice to give "some" flare. (No, the colors aren't on accident)

### Reflection
What I found from the plots was truly interesting. It seems, since 2013, Bryce Harper did better than Nolan Arenado and Manny Machado every
  odd year in every respect. But on every even year, he did worse than them in every respect. 
So, in this upcoming season, it will be interesting to see how Bryce Harper compares with the other two.
