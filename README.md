# 2019 Programming and Data Analysis Course

Welcome to the 2019 Programming and Data Analysis Course for the Undergraduate Research Program at Cold Spring Harbor Laboratory! This Github repository contains the Jupyter notebooks and data sets that we will work through in this course. 


## Summary

Repository URL: https://github.com/jbkinney/19_urp

Lead Instructor: 
- Justin Kinney (<jkinney@cshl.edu>), Assistant Professor

Teaching Assistants: 
- Shaina Lu (<slu@cshl.edu>), WSBS Student
- Benjamin Harris (<bharris@cshl.edu>), WSBS Student

Dates: 
- Tuesdays and Thursdays, 6/18 through 7/18 (except 7/4), 4:30pm - 6:00pm in the James Library (CSHL Main Campus).

Requirements:
- No prior programming experience is needed.
- Students must bring their own computers to each workshop.



## Overview

The ability to analyze large data sets and write custom scripts is quickly becoming an essential skill, both in academic biology and in the biotech industry.  This course aims to introduce these skills using the Python programming language, and is especially designed for students who are new to coding. Nine interactive workshops will be held:

- Workshop 1 (6/18): Introduction to Python and Jupyter Notebooks 
- Workshop 2 (6/20): Datatypes
- Workshop 3 (6/25): Flow control 
- Workshop 4 (6/27): Pandas, transcription factor binding site analysis
- Workshop 5 (7/2): Matplotlib, RNA-seq analysis
- Workshop 6 (7/9): Image analysis, cell segmentation
- Workshop 7 (7/11): Scikit-learn, data modeling
- Workshop 8 (7/16): 3rd party packages, single cell analysis
- Workshop 9 (7/18): Additional resources

If you decide to attend, please bring a laptop computer so that you can follow along and do the exercises. If you do not have a laptop, please let me know  so that we can make other arrangements. And finally, please **talk with your mentor so that you can plan your experiments and meetings ahead of time** to accommodate the schedule. 

## Instructions for use on Binder

Binder is a cloud environment that allows you to run Jupyter notebooks. We have found this the easiest way to run the code within this repository. Just click on the badge below. It often takes a few minutes to load, but once it's up and running it's reasonably fast. 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jbkinney/19_urp/master)

## Instructions for use on personal computers

This is the first year that we are using Binder. If for some reason this  doesn't work, students are asked to install the Anaconda distribution of Python 3.7 on their own computers. Here are the instructions for doing this.

Step 0 : Regardless of your computer, download this repository to your desktop and unzip it.

### Mac Instructions

1. Open a terminal window (Applications/Utilities/Terminal.app), type `cd /Desktop/19_urp/` at the command line, then hit enter. This should put you in the repository folder
1. Type `./mac_install.sh` at the command line and hit enter to run. Follow the prompts for installation: type `y` or `yes` when prompted with a y/n question, and hit enter when asked a non y/n question. This will install the Anaconda distribution of Python.
1. To run a notebook type `jupyter notebook` at the command line and hit enter. This will open up a web browser window. Then click on the name of the notebook that you would like to run.

### Windows Instructions

1. Go to this [website](https://docs.conda.io/en/latest/miniconda.html) and download the **64-bit (exe-installer)** in the table at the top of the site in the **Python 3.7** row for Windows 
1. Click the '.exe' file you downloaded and follow the prompts to complete the installation
1. Open the Anaconda prompt.
1. Type `conda install --file` at the prompt, but don't hit enter yet.
1. In Windows Explorer navigate to the /19_urp folder then drag the file titled `requirements_windows.txt` into the Anaconda Prompt and hit enter.
1. Answer `Y` or `Yes` to any y/n questions.
1. Type `pip install logomaker` at the prompt and hit enter.
1. Type `jupyter-notebook` at the prompt and hit enter.
