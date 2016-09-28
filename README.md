# ML-Workshop
#### Michael duPont - michael@mdupont.com

This is the workshop resource repository for the Machine Learning workshop at the Orlando Python meetup

## Installation

This project is designed for Python3.x (though it should still work for Python2.7) and uses the following libraries:

* [Scikit-Learn](http://scikit-learn.org/stable/)
* [Numpy](http://www.numpy.org)
* [Pandas](http://pandas.pydata.org)
* [Matplotlib](http://matplotlib.org)
* [Jupyter](http://jupyter.org)

Rather than installing these packages via pip3, it is recommended that they be installed via [Anaconda](https://www.continuum.io/downloads). It is a pre-compiled collection of scientific Python libraries.

## Running

To run the notebooks, open a terminal in the repository's directory and run `jupyter notebook`. This will open a Jupyter file browser in your default web browser.

The five Jupyter notebooks are in the root directory:

* **Intro to Scikit-Learn**: Introduction to concepts and terminology. Run through two basic supervised learning alorithms
* **Classifier Comparison**: Compares a variety of supervised classification models. Recreates the graphic on sklearn's home page
* **Affinity Propogation**: Example of an unsupervised clustering algorithm on randomized, generated blob data
* **Digits Classification**: Supervised classifier for handwritten digit recognition. Dataset sourced from MNIST
* **Eigen Faces**: Combines an unsupervised dimensionality reduction and a supervised classifier for facial recognition. Dataset sourced from the University of Massachetts

Press Shift-Enter to run a selected block.

Any pre-existing source code can be found in sklearn-source.  
Final HTML versions of the notebooks can be found in final-reports.