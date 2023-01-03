Data Source : Kaggle

## The Data
The CSV file consisted of three columns: Title, Year of Release and the IMDB rating. The data was presented in the descending order of IMDB rating. A new column indexing as *Rank* based on IMDB rating was added in zeroth position.

# Insights

![Boxplot year]("images/boxplot_year.png")  
![Boxplot rating]("images/boxplot_rating.png")  
![Histogram rating]("images/hist_combo.png")  
![Scatterplot: rating vs year]("images/scatter.png")  

## Correlation

To find any correlation between Year of Release (*Release_date*) and IMDB Rating (*Rating*) the correlation co-efficient was calculated based on data for top 250 rated movies. The value of r was found to be : 0.04069674149326002, which indicates weak positive relationship between the two variables. It is also evident from scatter plot between IMDB Rating and Year of Release.

The residual plot was found as follows:

![Residual plot]("images/residual.png")

# References
--------------
1. [Matplotlib - Pyplot : Documentation ](https://matplotlib.org/3.5.3/api/pyplot_summary.html)
