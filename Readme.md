# Analysis of airbnb Munich Data

I was wondering what to get out of the airbnb data from Munich. Driven by the initial question
what hosts and guests have to take into account when reasoning about prices of the appartments.

To narrow this down a bit, I started out with some descriptive statistics and then approached
explaining price peaks and variance in prices.

The full analysis can be found in this repository.

The results are also documented in a medium article: https://medium.com/@alex_14917/there-is-a-great-price-range-for-airbnb-offerings-in-munich-211c9dab7c4e
(DRAFT - to be updated after review)

## Getting the Data

The data is generously provided by airbnb at http://insideairbnb.com/get-the-data/.
You will need to download your own copy (whereto see below) to get the script running.

## Files in this Repository

This repository **contains** the following files:

**Readme.md**
: this file

**munich_analysis.ipynb**
: Jupyter notebook containing the analysis

**Munich_figures / * **
: All files in the folder are screenshots of the figures in the Jupyter notebook used for the medium articel

The notebook **requires** you to place the following files in these locations:

**Munich / calendar.csv**
: The calendar.csv file from airbnb

**Munich / listings.csv**
: The listings.csv file from airbnb
