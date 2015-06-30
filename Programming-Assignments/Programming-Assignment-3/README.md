Programming Assignment 3

Hospital Quality

There are three functions:- 

best         - that take two arguments:  the 2-character abbreviated name of a state and an 
               outcome name. The function reads the outcome-of-care-measures.csv file and returns 
               a character vector with  the name  of  the  hospital  that  has  the  best  
               (i.e.lowest)  30-day  mortality  for  the specified  outcome in that state. 

rankhospital - that takes three arguments:  the 2-character abbreviated name of a state (state), 
               an outcome (outcome), and the ranking of a hospital in that state for that outcome 
               (num).The function reads the outcome-of-care-measures.csv file and returns a 
               character vector with the name of the hospital that has the ranking specified by 
               the num argument.
               
rankall      - that takes two arguments: an outcome name (outcome) and a hospital ranking (num).
               The function reads the outcome-of-care-measures.csv file and returns a 2-column 
               data frame containing the hospital in each state that has the ranking specified in 
               num.
