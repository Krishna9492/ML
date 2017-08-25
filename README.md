# ml-python-class

Material developed for [Texas A&M University -
Commerce](http://tamuc.edu) course CSci 574: Introduction to Machine
Learning and Data Analysis.  These materials were developed in the
Fall of 2013 semester.  The original iPython notebooks were created in
2012 by Hannes Schulz, Andreas Mueller and Nenard Birešev at the
University of Bonn
[original github repo](https://github.com/amueller/tutorial_ml_gkbionics).  
I have taken the original material and expanded it for our course.

The materials have been updated for the Fall of 2015 semester.  Materials
from Dr. Ng Coursera [machine learning](https://www.coursera.org/learn/machine-learning/home/welcome) course were used extensively for the updates and assignments.

## Content

- The main content of the course will be delievers as interactive
  ipython/Jupyter notebooks.
- The lecture notebooks can be found in
  the lectures subdirectory, and all assignments for the course will
  be uploaded to the assignments subdirectory.



## More content

Suggested material for learning python:

- [Think Python: How to think like a computer scientist](http://www.greenteapress.com/thinkpython/) free online textbook, very good resource for not only Python but learning to program in general.
- [Google Developers Python Class](https://developers.google.com/edu/python/?hl=ru&csw=1) short course with videos, might be helpful for those looking for video tutorials of Python.
- [Software Carpentry](http://software-carpentry.org/v4/python/index.html) section on learning Python is also very good, and also includes videos.

Companion Textbooks on Machine Learning:

- Segaran. (2007). [Programming Collective Intelligence](http://www.amazon.com/Programming-Collective-Intelligence-Building-Applications/dp/0596529325/ref=sr_1_1?ie=UTF8&qid=1376624477&sr=8-1&keywords=segaran+programming+collective+intelligence).
  Already 6 years old, so a bit out of date, and as far as I know no new
  editions.  But I will develop some of my optimization and decision
  tree examples from here.   [Code examples](http://blog.kiwitobes.com/?p=44)

- Marsland. (2009). [Machine Learning: An Algorithmic Perspective](http://www.amazon.com/Machine-Learning-Algorithmic-Perspective-Recognition/dp/1420067184/ref=sr_1_1?ie=UTF8&qid=1376624555&sr=8-1&keywords=machine+learning+an+algorithmic+perspective).
  More examples of Python ML.  [Code examples](http://seat.massey.ac.nz/personal/s.r.marsland/MLbook.html)

- Conway & White. (2012). [Machine Learning for
  Hackers](http://www.amazon.com/Machine-Learning-Hackers-Drew-Conway/dp/1449303714/ref=sr_1_1?ie=UTF8&qid=1376624747&sr=8-1&keywords=machine+learning+for+hackers). [github repo of book source and data](https://github.com/johnmyleswhite/ML_for_Hackers)
  Case studies for this book are written in R.  This site 
  [Will it Python](http://slendrmeans.wordpress.com/will-it-python/)
  has example reimplementations in iPython notebooks.
  


## Installing Python

For a true interactive use of the notebooks (which you are required to
use if you are taking the class) you need to install Python, IPython and Jupyter
(for notebooks) and the required libraries scikit-learn, matplotlib
and numpy.

### Windows & Mac Users

You can install everything at once using a complete scientific Python distribution.
Two good ones are the [Enthought Canopy Python distribution](http://www.enthought.com/products/epd.php)
or the [Anaconda Distribution](http://www.continuum.io/downloads).

Recently I have begun recommending and preferring the Anaconda distribution
for Window.  This [video](http://derekharter.com/class/fall2013/csci538/0-windows-python-install.webm)
has an example of installing a Python distribution
on a Windows system, as well as install git and using it to get the course
repository and view the notebooks in Jupyter.


### Linux

You can use the Anaconda distribution mentioned above, or simply
use your package manager from your linux distribution to install the
needed Python and iPython packages by hand. For example on Ubuntu or Debian, use
``apt-get install python ipython python-matplotlib python-numpy python-sklearn``
to get started..

## Version requirements

You need to make sure to have at least IPython >= 0.11 installed. You can update using the programm ``easy_install``.

## Installing Scikit-learn

More tips on installing scikit-learn can be found on the [scikit-learn website](http://scikit-learn.sourceforge.net/dev/install.html#installing-an-official-release).  If you used the Enthought Python distribution, I believe they will be installed for you as part of that distribution.


## More Resources

- The [scikit-learn example gallery](http://scikit-learn.sourceforge.net/dev/auto_examples/index.html) and [user guide](http://scikit-learn.sourceforge.net/dev/user_guide.html).
- [Videos and presentations](http://scikit-learn.sourceforge.net/dev/presentations.html) on machine learning and scikit-learn.
- The [matplotlib example gallery](http://matplotlib.org/gallery.html).
- [Numpy for matlab users](http://www.scipy.org/NumPy_for_Matlab_Users).

