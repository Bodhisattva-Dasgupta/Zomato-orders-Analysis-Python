**Zomato Restaurant Data Analysis Using Python**

*Project Overview*

This project explores Zomato restaurant data using Python to understand restaurant categories, customer ratings, restaurant votes, approximate dining costs, and online ordering patterns. It uses data analysis and visualization libraries to summarize the dataset and present findings through charts.

The project is implemented in a Jupyter Notebook (Code.ipynb).

*Objectives:*
Explore the types of restaurants listed in the dataset.
Compare the number of restaurants across restaurant categories.
Examine the total votes received by each restaurant category.
Understand the distribution of restaurant ratings.
Explore the approximate cost for two people.
Compare average ratings for restaurants that accept online orders and those that do not.
Compare online-order availability across restaurant categories.

*Tools and Libraries*

Python — programming language used for the analysis.
Pandas — loading, inspecting, grouping, and analyzing tabular data.
NumPy — numerical computing library.
Matplotlib — creating charts and plots.
Seaborn — creating statistical visualizations.
Jupyter Notebook — developing and executing the analysis.

*Analysis and Visualizations*

1. Restaurant Categories
The project counts restaurants in each category using the listed_in(type) column and displays the counts in a bar chart.

2. Votes by Restaurant Category
The total number of votes is calculated for each restaurant category by grouping the data by listed_in(type) and summing the votes column. A line plot is used to compare the category totals.

The notebook records the following observations:
Dining restaurants receive the highest total number of votes, approximately 20,000.
Other restaurant types follow, with approximately 9,500 votes.
Cafes receive approximately 6,500 votes.
Buffet restaurants receive the fewest total votes, approximately 3,000.
These figures are observations recorded in the notebook and may depend on the dataset version used.

3. Distribution of Restaurant Ratings

A histogram is used to examine how restaurant ratings are distributed. The notebook records that most restaurants have ratings between 3.5 and 4.
Before plotting, the /5 text is removed from the rate column, and the values are converted to a numeric data type.

4. Approximate Cost for Two People

A count plot displays the number of restaurants across different values of approx_cost(for two people).
The notebook records that the approximate cost value most commonly observed is 300.

5. Average Ratings: Online vs. Offline Orders

The mean rating is calculated for each value in the online_order column and visualized with a bar plot.
This analysis compares the average ratings of restaurants that accept online orders with those that do not.
The notebook's conclusion is that restaurants accepting online orders receive higher ratings. However, this comparison alone does not establish that online ordering causes higher ratings.

6. Online Ordering Across Restaurant Categories

A count plot compares online-order availability across restaurant categories using the listed_in(type) and online_order columns.
The notebook records that dining restaurants primarily accept offline orders, whereas cafes accept online orders. This observation applies to the dataset analyzed and should not automatically be generalized to all restaurants.

*Key Findings*

Based on the observations recorded in the notebook:
Dining is identified as the largest or preferred restaurant category.
Dining restaurants have the highest total number of votes among the categories shown.
Most restaurant ratings fall between 3.5 and 4.
The approximate cost value most commonly observed for two people is 300.
The analysis compares average restaurant ratings according to online-order availability.
Online-order availability differs across restaurant categories.

These findings reflect the notebook's current written observations and have not been independently verified against a separately supplied dataset.
