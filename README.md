# ASO - Keyword Optimisation Cycle Script

A simple Python script for measuring the effects of the keyword optimisation cycle

Accepting pull requests!

## What does it do?

You put in your metadata before and after a change, your keyword list and the rankings before and after the change. 

From this, it will tell you the average improvement/drop in every keyword that has a word contained in your metadata change.

## Getting Started

- Download the folder from Github
- Fill in the format.csv folder with your previous app metadata, and the changes you made.
- Fill your keyword list in the same file, and the ranking before and after the change.
- Launch Jupyter notebook and open the file, run through the code.
- You'll be left with an 'output.csv' file with the average change that has occurred to all the keywords you're tracking that are contained within your metadata. 

## Motivation
Implementing and scaling a keyword optimisation cycle can be difficult and time consuming. I wanted a script to automate the process of evaluating how my keyword changes impacted rankings.

### Roadmap

- Manage changes in relative weight of keywords, e.g. keyword moving from the title to the subtitle/short description.
- Take into account the Search Popularity to evaluate the impact of each keyword change.
- Remove non-valuable words like 'and, an, for' etc.
- iOS keywords support

## Built With
Python, Jupyter, Pandas, Numpy

## Authors

* **Fede Behrens** - *Initial work* - [Fede Behrens](linkedin.com/in/behrensfede)
