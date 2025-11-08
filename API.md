# Midterm Project - API FILE

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
This program examines the **Global Coffee Health Dataset** on Kaggle: https://www.kaggle.com/datasets/uom190346a/global-coffee-health-dataset/data

### The program contains ten main functions:
`verifyFile()`
This function verifies if the input file exists, if the file name is empty then it defaults to a specified file
* Parameters: file name and file type
* Outputs: data frame or csv file

`dataClean()`
Converts all 0s and 0.0s in a column to None.
* Parameters: data frame and column name
* Output: udpated data frame

`calcMax()`
Finds the maximum value in the input list.
* Parameters: column or list 
* Output: maimum value in float

`calcMin()`
Finds the minimum value in the input list.
* Parameters: column or list 
* Output: minimum value

`calcMean()`
Calculates the mean in the input list.
* Parameters: column or list
* Output: mean in float

`calcStdDev()`
Calculates the standard deviation of the input list.
* Parameters: column or list
* Output: standard deviation in float

`calcMode()`
Calculates the mode value in the input list.
* Parameters: column or list
* Output: mode in float

`calcCov()`
Calculates the covariance value for the x and y variables.
* Parameters: data frame, row label for x, mean for x in float, row label for y, mean for y in float
* Output: covariance in float

`calcCorr()`
calculates the correlation coefficient for the x and y variables.
* Parameters: covariance in float, standard deviation for x in float, standard deviation for y in float
* Output: correlation coefficient in float

`calcCorrStrength()`
Identifies what category of strength the correlation falls under: strong positive, positive, negative, strong negative, and weak.
* Parameters: correlation coefficient in float
* Output: category in string

`linReg()`
Calculates the slope and y-intercept based on inputs.
* Parameters: correlation, standard deviation for x, standard deviation for y, mean for x, mean for y all in float
*Output: slope and y-intercept in float

`predY()`
Predicts the y value for an x value. In this case the y value is `Sleep_Hours` and x value is `Coffee_Intake`. Gives us a calculated guess of how many hours of sleep will an individual get if they drink a specific number of cups of coffee.
* Parameters: slope, y-intercept, and input x value all in float
* Output: y value in float

`cleanOutput()`
Prints the inputted information to the `.txt` file as well as the console for quick viewing.
* Parameters: label and value type in string, value in its original type
* Output: String statement
