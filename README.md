# NYC COVID-19 Transportation Analysis

## Group Members
1. [Jason Lai](https://github.com/M2JT)
2. [Kewei Zhang](https://github.com/jeffzhkw/)

## Introduction
The COVID-19 pandemic has had an unprecedented impact on our way of life, particularly in terms of transportation. In this study, we sought to explore the effects of lockdown measures on public transportation in the New York City area. Specifically, we analyzed data from two primary sources of transportation, namely the MTA subway turnstile usage and Citi Bike trip data, spanning from year 2019 to 2022. By examining patterns in public transportation usage before, during, and after the pandemic, we aimed to identify any significant changes in people's transportation behavior, as well as to explore whether a "new normal" has emerged in the post-COVID period.

## Instructions for Reproducing Our Work

### In the Data Directory
1. Unzip all files in the [citibike](https://github.com/M2JT/big-data-final-project/tree/main/data/citibike) directory
2. Due to size limits, we could not upload the subway data for 2019, 2020, and 2022. Should you wish to reproduce our subway analysis, please contact [Jason Lai](mailto:jl9338@nyu.edu) to acquire all the CSV files

### In the Code Directory
1. Make sure [Anaconda](https://www.anaconda.com/) is correctly installed on your machine
2. Install Jupyter Notebook in Anaconda
3. In terminal (Mac) or command prompt (Windows), run `conda install openjdk` to install Java
4. Run `conda install pyspark` to install PySpark on Anaconda
5. Run `conda install -c conda-forge findspark` to enable PySpark to be run in Jupyter Notebook
6. Run `conda install matplotlib` to install Matplotlib data visualization library in your current environment
7. Run `conda install pandas` to install pandas in your current environment
8. All set! Now by clicking `Run All` in the Notebook, you should be able to reproduce all of our work