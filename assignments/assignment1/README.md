## Assignment 1: Plots and probability distributions
Assignment Date: Monday, September 18, 2017<br>
Due Date: Monday, September 25, 2017 @ 11:59pm <br>

### Assignment Overview

In this assignment, you will explore a few properties of the binomial, normal, and Poisson distribution. I encourage you to discuss your solutions with other members of the class, but everyone should submit their own code. You are allowed to use the notes from class, and notes found online to help you work through the problem. Here are a few helpful resources:

- [Python 2 reference](https://docs.python.org/2/reference/index.html)
- [Jupyter notebooks](http://jupyter.org/)
- [Matplotlib](https://matplotlib.org/) and [Gallery](https://matplotlib.org/gallery.html)
- [Numpy](http://www.numpy.org/) and [Scipy](https://www.scipy.org/)


#### Question 1. Binomial Distributions [10 pts]

- Question 1a. Modify the coin flip example to print 100 flips from an unbalanced coin where p(heads) = 40% [Hint: adjust random.randint()]

- Question 1b. Plot the density of heads after 1,000 trials with 100 flips of the unbalanced coin [Hint: see notes]

- Question 1c. What is the mean and standard deviation of the flip results after 1,000, trials 10,000 trials, 50,000 trials, or 100,000 trials? Make a line plot of the relationship between the standard deviation and the number of trials [Hint: see notes]

- Question 1d. Overlay the binomial and normal distributions on the 1,000 trial density using the 1,000 trial mean and stdev [Hint: see notes]

- Question 1e. What is the probability of seeing 25 heads in 100 flips from this unbalanced coin? [Hint: see notes]


#### Question 2. Poisson Distributions [10 pts]

The [Poisson distribution](https://en.wikipedia.org/wiki/Poisson_distribution) is another common distribution that is frequently involved in scientific data, especially when looking at count data. A simple example of it is a "balls in bins" experiment where N balls are distributed into M bins with uniform probability and then counting how many balls are present in each in each bin.

- Question 2a. Implement a simulation where you distribute 200 balls into 100 bins. print the number of balls in each bin at the end of the simulation. [Hint: use a list to record how many balls are in each bin, and use random.randint() to figure out where each ball should land]

- Question 2b. What is the mean and standard deviation of the number of balls in each bin?

- Question 2c. Plot a histogram of the distribution of the number of balls distributed into each bin, and overlay with a normal distribution.

- Question 2d. Is the normal distribution a good fit for the distribution?

- Question 2e. Repeat steps 2a through 2d but distributing 2,000 balls into 100 bins (implement, compute mean/stdev, plot, overlay, evaluate)


### Packaging

The solutions to the above questions should be submitted as a single Jupiter notebook (.ipynb) that includes your name, email address, and all relevant figures and text (as needed). Make sure to clearly label each of the subproblems and clearly label your plots. Submit your solutions by emailing the document as an attachment to "jhubiomedicalresearch at gmail dot com" by 11:59pm on Sept 25. Name your file as "Lastname.Firstname.Asn1.ipynb" (replace LastName.Firstname with your own name :-). If you submit after this time, you will start to use up your late days. Remember, you are only allowed 4 late days for the entire semester!


