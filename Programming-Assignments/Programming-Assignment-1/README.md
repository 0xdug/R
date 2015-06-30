Programming Assignment 1 

There are three functions:-
pollutantmean - calculates the mean of a pollutant (sulfate or nitrate) across a specified list of monitors

complete      - reads a directory full of files and reports the number of completely observed cases in each data file. 
                The function should return a data frame where the first column is the name of the file and the second 
                column is the number of complete cases.

corr          - takes a directory of data files and a threshold for complete cases and calculates the correlation between 
                sulfate and nitrate for monitor locations where the number of completely observed cases (on all variables) 
                is greater than the threshold.
       
