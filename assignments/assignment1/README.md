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

- Question 1a. Modify the coin flip example to print 100 flips from an unbalanced coin where p(heads) = 40% [Hint: adjust random.randint() and adjust your test for heads]

- Question 1b. Plot the density of heads after 100 trials, 1000 trials, or 10,000 trials with 100 flips of the unbalanced coin? Qualitatively describe how the distribution changes with more trials.

- Question 1c. What is the mean and standard deviation of the flip results after 10,000 trials? Overlay the binomial and normal distributions on the plots from 1b

- Question 1d. What is the probability of seeing 25 heads in 100 flips from this unbalanced coin (p(heads) = .4)? Is this a statistically signficant result?

- Question 1e. What happens to the  mean and standard deviation if there are more flips per trial? Make a plot of the meand and standard deviation after 1,000 trials with 100 flips, 1,000 trials with 1000 flips, or 1,000 trials with 10,000 flips. Also plot the densities of these 3 different experiments.


#### Question 2. Poisson Distributions [10 pts]

The [Poisson distribution](https://en.wikipedia.org/wiki/Poisson_distribution) is another common probability distribution that is frequently needed from analyzing scientific data, especially count data. A simple example of it is a "balls in bins" experiment where N balls are distributed with uniform random probability into M bins and then counting how many balls are present in each in each bin. Other examples include comparing differences in gene expression data, examining firing rates of neurons, or predicting the length of the line at the grocery store (and many, many others)

- Question 2a. Implement a simulation where you randomly distribute 200 balls into 100 bins. Print the number of balls in each bin at the end of the simulation. [Hint: modify the dart throwing code to look at how many darts land in each bin]

- Question 2b. What is the mean and standard deviation of the number of balls in each bin? [Hint: the dart throwing code looks at the distance between darts, here we are looking at the number of darts per bin)

- Question 2c. Plot a histogram of the distribution of the number of balls distributed into each bin, and overlay with a normal distribution.

- Question 2d. Is the normal distribution a good fit for the observed distribution?

- Question 2e. Repeat steps 2a through 2d but distributing 2,000 balls into 100 bins (Hint: make sure to do all steps: implement, compute mean/stdev, plot, overlay, evaluate)


### Packaging

The solutions to the above questions should be submitted as a single Jupiter notebook (.ipynb) that includes your name, email address, and all relevant figures and text (as needed). Make sure to clearly label each of the subproblems and clearly label your plots. Submit your solutions by emailing the document as an attachment to "jhubiomedicalresearch at gmail dot com" by 11:59pm on Sept 25. Name your file as "Lastname.Firstname.Asn1.ipynb" (replace LastName.Firstname with your own name :-). If you submit after this time, you will start to use up your late days. Remember, you are only allowed 4 late days for the entire semester!


