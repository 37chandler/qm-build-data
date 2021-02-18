# Building Regression Data

In this assignment we continue the exercise we did in class. You should
come up with a real world application of regression and determine response
and explanatory variables. 

This assignment is meant to be relatively fast, but there _is_ a catch. This
assignment has to be completed within one week, so we can continue working
with the data you create next week. 

Then I'd like you to create a synthetic data set. This data set 
should allow someone to use regression to estimate the relationship
between the variables. Some things that you can include:

* Non-linear relationships such as squaring one of the terms. 
* Variance structures that require a transformation. For instance, an 
  error that grows with the value of the data. 
* Terms in the data set that *don't* influence the response variable. 

After you've made your data set, I'd like you to make a short R Markdown
document that does a brief exploratory data analysis on the data you've made.
Plot the distributions. Feel free to plot interesting scatter plots. Calculate
summary statistics. Tell people the units a variable is in, etc. The knitted
version of this document will accompany the data set for your ~marks~ audience. 

I've included a short file that synthesizes the traffic accident data set 
I mentioned in class. Linear regression isn't perfect for this data set, but
it will get the job done. 

