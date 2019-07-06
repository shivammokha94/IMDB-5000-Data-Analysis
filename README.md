# IMDB-5000-Data-Analysis
Analysis of IMDB 5000 dataset along with Logistic Regression models to find a profitable blockbuster movie


This repo consists of dataset for IMDB 5000 movies. The code described goes through data cleaning, data exploration, preprocessing  and its analysis. Furthermore, I run logistic regression models to find if the given  movie is a blockbuster. The criteria to determine if a movie is a blockbuster is defined as follows:

1.	For a movie with a budget less than $5million, gross over $2million and having a profit greater than 500% of net.
2.	For a movie with a budget more than $5mil having a profit greater than 150% of net.
If these conditions are satisfied, the blockbuster column is marked as 1, else 0.

The train and test sets are splits in the ratio 7:3. The first logistic regression gives us an accuracy to about .97 and this includes gross values for each movie. From the F-statistic and t-statistic, we can see the adjusted R-square of .385, which is the percentage of variation of data that can be explained. If the gross column is removed, the accuracy decreases to 0.83. Finally, using Principal Component Analysis (PCA), to reduce the number of dimensions to 3 which explains about 21% of variations in data and the accuracy is retained at 0.81.
