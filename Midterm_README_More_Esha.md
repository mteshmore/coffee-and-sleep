# Midterm Project - README FILE

Esha More\
Instructor: Dr. Mager Elshakankiri

Course code: INF1340\
Course name: Programming for Data Science\
Program: Master of Information\
Faculty of Information\
University of Toronto

Date Created: 2025-10-18\
Date Modified: 2025-10-18

## Introduction
This program examines the **Global Coffee Health Dataset** on Kaggle and performs basic data analysis on the Coffee Intake and Sleep Hours variables present. It also conducts a prediction of sleep hours based on coffee intake. The output of the analysis is formatted in user-friendly manner and printed to the console and to a user-specified file.

This project was implemented without the use of any imported libraries or built-in mathematical functions.

## Running the Program
To run the program download the file `Midterm_More_Esha.py` and the dataset `coffee-health.csv` on Kaggle: https://www.kaggle.com/datasets/uom190346a/global-coffee-health-dataset/data

Run the program through the terminal and follow the prompts to enter the names of the input and output files.

```python
Midterm_More_Esha.py
Enter the input file name: coffee-health.csv
Enter the output file name: midterm-results.txt
```

The following output is printed to the console and to the `midterm-results.txt` when executing the program using the dataset on Kaggle.

### Descriptive Statistics
We start by showing the minimum and maximum values for the `Coffee_Intake` variable, as well as the mean, standard deviation, and mode for both `Coffe_Intake` and `Sleep_Hours`

### Correlation
Additionally the user is provided values on covariance, correlation, and gives us a strength category to determine the relationship betweeon `Coffee_Intake` and `Sleep_Hours`.

### Prediction
Lastly, we conduct a linear regression on the two variables and create an algorithm to predict how many hours someone would sleep based on cups of coffee consumption daily on average. Using the coffee input value from the user we predict how many hours of sleep someone who drinks that many cups would get.