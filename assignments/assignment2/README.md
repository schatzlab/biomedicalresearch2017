## Assignment 2: Genome Assembly
Assignment Date: Wednesday, October 25, 2017<br>
Due Date: Monday, November 6, 2017 @ 11:59pm <br>

### Assignment Overview

In this assignment, you will explore a few properties of the sequencing data. 
You can either submit your results in a jupiter notebook, or as a single PDF document.
Feel free to sketch the figures by hand, and then include a photograph of your solution.
I encourage you to discuss your solutions with other members of the class, but 
everyone should submit their own write up. You are allowed to use the notes from class, 
and notes found online to help you work through the problem. 

Here are a few helpful resources:

- [Python 2 reference](https://docs.python.org/2/reference/index.html)
- [Jupyter notebooks](http://jupyter.org/)
- [Matplotlib](https://matplotlib.org/) and [Gallery](https://matplotlib.org/gallery.html)
- [Numpy](http://www.numpy.org/) and [Scipy](https://www.scipy.org/)


#### Question 1. Read coverage [10pts]

1a. The cichlid fish genome is 1 Gbp. Approximately how many 100bp reads should we sequence so that we expect at least 99.85% of the genome will be sequenced at least 40 times? (Hint: show your work)

1b. Sketch the expected coverage distribution for this number of reads; be sure to clearly label the mean coverage, and how 40 fold coverage relates to the mean. (Hint: In a normal distribution, 68.2% of the data will be within 1 standard deviation, 95.4% within 2, 99.7% within 3, and 99.9% within 4)

1c. Why might you want to sequence the genome any deeper than this? (In a few sentences)


#### Question 2. de Bruijn graph construction [10pts]

2a. Draw the de Bruijn graph for the following reads using k=3 (assume all reads are from the forward strand, no sequencing errors, complete coverage of the genome)

    ATTC
    ATTG
    CATT
    CTTA
    GATT
    TATT
    TCAT
    TCTT
    TGAT
    TTAT
    TTCA
    TTCT
    TTGA

2b. Write one possible genome sequence from this graph 
(Hint: your solution should visit every node in the graph at least once)

2c. Why might you want to use longer reads? (In a few sentences)

### Packaging

The solutions to the above questions should be submitted as a single Jupiter notebook (.ipynb) 
or single PDF document (.pdf) that includes your name, email address, and all relevant figures
and text (as needed). Make sure to clearly label each of the subproblems and clearly label 
your plots. Submit your solutions by emailing the document as an attachment 
to "jhubiomedicalresearch at gmail dot com" by 11:59pm on Nov 6. 

Name your file as "Lastname.Firstname.Asn2.ipynb" or "Lastname.Firstname.Asn2.pdf" 
(replace LastName.Firstname with your own name :-). If you submit after this time,
you will start to use up your late days. Remember, you are only allowed 4 late days 
for the entire semester!


