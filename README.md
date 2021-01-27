# IMDb-Movie-Reviews
We have the data for the 100 top-rated movies from year 2010 to 2016 along with various pieces of information about the movie, its actors, and the voters who have rated these movies online. 
In this project, we will try to find some interesting insights into these movies and their voters.

# How we will proceed
I would like to state that the whole analysis has been done on Python and the platform is Jupyter notebook. Anyone who has prelim knowledge of the language can easily understand the code.
Before I begin I would like to set the expectations of this article. **This article aims to make you think like an analyst, how to approach a business problem analytically, what is the business logic behind it, etc.** It contains simple python codes, basic viz, and no predictive modeling — because the objective here is not to share knowledge on coding or any high-level stats. 
**Since it would be a bit long blog, my suggestion to the readers would be not to read this all at once, try breaking them in parts, and whenever you think it’s too much, just stop! bookmark the page and come back after having a cup of coffee!!**

Enough of talking let’s dive into it:

#### Link to IMDb dataset and data description

[IMDb data set](https://drive.google.com/drive/folders/1WiD9EC0Qqc_bWdn93-_kxYtiP48Wlb-v?usp=sharing)

#### “Your approach is your key to success”

A scientific approach should be followed for solving any business problem using data we have in hand to derive valuable insights and recommendations.

![Process](https://user-images.githubusercontent.com/17608830/105930616-e84e1600-606f-11eb-8c1d-76d3dc47e7a6.png)

My suggestion to everyone would be not to see the code or explanation at first. Read the various steps and try to solve it on your own, give some time to it, and when you think its enough then look into the various code chunks and explanations!

#### Good Luck!! :-D

First, we’ll carry out the usual steps needed for the analysis after that slowly we’ll start building context and solve problems.

# Importing libraries
* Numpy
* Pandas
* Manplotlib
* Seaborn
