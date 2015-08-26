# Introduction to Statistics

Inspired by Allen Downey's books [Think Stats](http://greenteapress.com/thinkstats/) and [Think Bayes](http://greenteapress.com/thinkbayes/), this is an attempt to learn Statistics using an application-centric programming approach. 

## Objective
Showcase real-life examples and what statistics to use in each of those examples. Almost every book teaches a concept and shows an example. Ultimately, every topic gets treated separately and no holistic view is presented. Here, we would take examples and see how to make sense out of it. 

## Topics covered

* Mean, Median, Mode
* Standard Deviation
* Variance
* Co-variance
* Probability Distribution
* Hypothesis Testing
* t-test, p-value, chi-squared test
* Confidence Intervals
* Confidence levels and Sigificance levels
* Correlation
* Resampling (and uses in Big Data)
* A/B Testing
* A simple linear regression model

## Workshop Plan
We would be using rainfall data of Indian districts (Data to be uploaded to the repo)

There will be separate ipython notebooks - grouped by topic similarities.

* Find sum of rainfall in a year, by various districts.
* Find mean of rainfall in a year, by various districts
* Find variance of rainfall in selected districts. Find variance of selected states
* Define distribution. Plot histograms
* Determining outliers (Plots, quantiles, box plots, percentiles) in rainfall data
* Continuous distributions(exponential distribution, normal distribution)
* Introduction to Probability
* Hypothesis testing. Check if rainfall across districts in a state are similar or not. Check for states, regions
* Resampling
* Simple regression model: Predict rainfall for next year. Understand the output and diagnostics
* A/B testing:(We will be using marketing data):Check if marketing campaign was successful or not.


## Prerequisites
* Basics of Python. User should know how to write functions; read in a text file(csv, txt, fwf) and parse them; conditional and looping constructs; using standard libraries like os, sys; lists, list comprehension, dictionaries
* It is good to know basics of the following:
    * Numpy
    * Scipy
    * Pandas
    * Matplotlib
    * Seaborn
    * IPython and IPython notebook - Everything here would be an IPython notebook
* Software Requirements
    * Python 2.7
    * git - so that this repo can be cloned :)  
    * virtualenv
    * Libraries from *requirements.txt*

## Optional
Users could choose to install Anaconda, if they want. Disclosure: I use Anaconda

## Setup Guide

####Clone the repository
    $ git clone https://github.com/rouseguy/intro2stats.git

####Create a virtual environment & activate
    $ cd intro2stats
    $ virtualenv env
    $ source env/bin/activate

####Install reqirements from requirements file
    $ pip install -r requirements.txt

####Note: Make sure you have libraries for png & freetype.
Ubuntu users can install the below

    apt-get install libfreetype6-dev
    apt-get install libpng-dev
