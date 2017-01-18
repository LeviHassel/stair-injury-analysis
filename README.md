# Stairs Interpolation

### Contributors
Levi Hassel

## Overview
Check out the [full report](/report.pdf "Stair Injury Analysis Report").

## Project Organization
There are three MATLAB programs: sumOfRectangles.m, trapezoid.m and simpsons.m. These are NOT general use functions. They are designed specifically for output in terms of this project. stairs.m is For more info, check out the [full report](/report.pdf "Stair Injury Analysis Report").

## Requirements
Open stairs.m and change the filepath in single quotes for both age and chance to your directory's filepath + '\injurydata.csv'. and save the file.

## How to Run
Every function is of the form function_name(f,a,b,h) where:
 * f is the f(x) vector, containing probability values
 * a is the starting year
 * b is the ending year
 * h is the distance (in years) between each evaluated data point (must be at least 1)

Run each as function_name(stairs.chance,a,b,h) in the MATLAB command window using an a, b and h of your choice (note that h=1 will always be the most accurate option). For example, if you want to find the probability of someone going to the ER for a stair-related injury between the ages of 5 and 75, you would type `function_name(stairs.chance,5,75,1)`.

## Expected Output
These programs do not return values, they only print off the answers. All answers are multiplied by 100 in order to show them in terms of percentages, the way the report displays probability.

## References
See [report](/report.pdf "Stair Injury Analysis Report")