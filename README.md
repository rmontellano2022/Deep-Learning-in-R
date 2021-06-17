# Deep Learning in R
This is the repository for D-Lab's R-Graphics workshop. Laptop, Internet connection, and Zoom account required.

**Prior experience with R is assumed such as R-Fundamentals Parts 1 through 4 or equivalent knowledge.
This is an advanced level workshop which requires participants to be intermediate R users and have had some prior exposure to machine learning.**

# Workshop Goals

Need to talk to team #1

# Installation Instructions
In preparation for the upcoming workshop you will need to install R, RStudio, the necessary packages, Anaconda, and the workshop materials. Please perform these steps before the start of the workshop - they can take up to an hour to complete.

1. Install R

Download R by clicking the link here: https://cloud.r-project.org/

Select your operating system and then click "base" (Windows users) or "R-4.0.3.pkg". Double-click this file once it has finished downloading and follow the instructions to install it.

2. Install RStudio

Download RStudio by visiting this link: https://rstudio.com/products/rstudio/download/

Scroll down and click the Download button beneath "RStudio Desktop - Open Source License - Free". Double-click this file once it has finished downloading and follow the instructions to install it.

3. Install the necessary packages

Install Keras by running these commands in the RStudio console or an R script:
This will install the keras R package.
install.packages("keras")

This will setup the Python environment, including Keras and tensorflow.
keras::install_keras()

Confirm that Python setup was successful - this must return "TRUE".
keras::is_keras_available()
Install Image Magick
install.packages("magick")
library(magick)
4. Anaconda notes
Anaconda is required on Windows, whereas MacOS and Linux may be ok without it. However it will be easiest to manage & troubleshoot when everyone is using Keras through Anaconda.
Install Anaconda here: https://docs.anaconda.com/anaconda/install/ 
MacOS users with R installed via Homebrew, or Linux users, see extra install info here.
5. Download the workshop materials

Download the workshop materials by visiting the GitHub repository: https://github.com/dlab-berkeley/Deep-Learning-in-R 

To download the repository, click the green button in the top right hand corner that says "Code" and then select "Download ZIP". You can then unzip the contents of the downloaded folder somewhere accessible on your local computer (we recommend your Desktop).

We will take a few minutes at the start of the workshop to make sure everyone has R and RStudio installed and the workshop materials downloaded. Please feel free to email dlab-frontdesk@berkeley.edu or visit our help desk at https://dlab.berkeley.edu/frontdesk if you have any questions.

If you are a Git user, simply clone this repository by opening a terminal and typing: “git clone https://github.com/dlab-berkeley/Deep-Learning-in-R.git”.


# Is R not running on your laptop?



# Run the code! 

Make instructions

# How to get help?

* Videos
    * J.J. Allaire [talk at RStudioConf 2018](https://www.rstudio.com/resources/videos/machine-learning-with-tensorflow-and-r/)

# Resources

* D-Lab [Machine Learning Working Group](http://dlab.berkeley.edu/working-groups/machine-learning-working-group-0)

* Websites
    * RStudio [Keras](https://keras.rstudio.com/)
    * Supplementary [notebook materials](https://github.com/jjallaire/deep-learning-with-r-notebooks)

* Massive open online courses
    * [fast.ai - Practical Deep Learning for Coders](https://course.fast.ai/)
    * [Kaggle Deep Learning](https://www.kaggle.com/learn/deep-learning)
    * [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course/)
    * [See this](https://developers.google.com/machine-learning/crash-course/fitter/graph) sweet interactive learning rate tool
    * [Google seedbank examples](https://tools.google.com/seedbank/seeds)
    * [DeepLearning.ai](https://www.deeplearning.ai/)
    
* Workshops
    * [Nvidia's Modeling Time Series Data with Recurrent Neural Networks in Keras](https://courses.nvidia.com/courses/course-v1:DLI+L-HX-05+V1/about)

* Stanford
    * CS 20 - [Tensorflow for Deep Learning Research](http://web.stanford.edu/class/cs20si/syllabus.html)
    * CS 230 - [Deep Learning](http://cs230.stanford.edu/)
    * CS 231n - [Neural Networks for Visual Recognition](http://cs231n.github.io/)
    * CS 224n - [Natural Language Processing with Deep Learning](http://web.stanford.edu/class/cs224n/)

* Berkeley
    * Machine Learning at Berkeley [ML@B](https://ml.berkeley.edu/)
    * CS [189/289A](https://people.eecs.berkeley.edu/~jrs/189/)

* UToronto CSC 321 - [Intro to Deep Learning](http://www.cs.toronto.edu/~rgrosse/courses/csc321_2018/)

* Books
    * F. Chollet and J.J. Allaire - [Deep Learning in R](https://www.manning.com/books/deep-learning-with-r)
    * Charniak E - [Introduction to Deep Learning](https://mitpress.mit.edu/books/introduction-deep-learning)  
    * I. Goodfellow, Y. Bengio, A. Courville - [www.deeplearningbook.org](https://www.deeplearningbook.org/)
    * Zhang et al. - [Dive into Deep Learning](http://en.diveintodeeplearning.org/) 
    
* Python
    * [Qingkai Kong's Artificial Neural Network Fundamentals in Python](https://github.com/dlab-berkeley/ANN-Fundamentals)


# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use R for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops such as R Fundamentals, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.  

Visit the [D-Lab homepage](http://dlab.berkeley.edu/) to learn more about us. View our [calendar](http://dlab.berkeley.edu/calendar-node-field-date) for upcoming events, and also learn about how to utilize our [consulting](http://dlab.berkeley.edu/consulting) and [data](http://dlab.berkeley.edu/data-resources) services. 

(include definition of IOKN2K!)

# Other D-Lab R Workshops

Check out the [D-Lab Computational Text Analysis Working Group by clicking here](http://dlabctawg.github.io/)

### Basic competency



### Intermediate/advanced copmetency



### Legacy workshops (need updating)


# Contributors 


---
<div style="display:inline-block;vertical-align:middle;">
<a href="https://dlab.berkeley.edu/" target="_blank">
<img src ="https://dlab.berkeley.edu/sites/default/files/logo.png" width="60" align="left" border=0 style="border:0; text-decoration:none; outline:none">
</a>
</div>
<div style="display:inline-block;vertical-align:middle;align:left">
    <div style="font-size:larger">D-Lab @ University of California - Berkeley
    </br>
    <a href="https://dlab.berkeley.edu" target="_blank">https://dlab.berkeley.edu</a>
    </br>
    &nbsp;
    </div>
</div>
