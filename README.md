# CSU Bakersfield - CMPS 3500 Group Project
This is a basic data analysis program in Python that reads in a .csv file, processes, organizes, then displays the output data to the user.

For this project, we were given a 700,000+ line .csv file of real traffic accidents in the United States from 2016 to 2021.
Our objective was to write a program that was easy to read and navigate with useful comments, minimal errors, and optimal runtimes.
Our group's workflow was to first load and process the data using the 'Pandas' library in Python and test our program with smaller data sets before loading in our real data set. The main focus was basic functionality and reliability. 
After we had processed and organized the data, we began implementing Question and Search functions to allow the user to find that necessary information from the .csv file in a quick and efficient manner.
Once question and search functions were completed, we began working on the user interface development, formatting, and error handling.

The general logic for the Search Capability is:
	
	- accept user input as arguments
	- validate that input
	- convert strings to the appropriate data type (if necessary)
	- filter the conditions
	- handle blank or empty input using if/else statements
	- return # of rows that satisfy the conditions
	
The general logic for the Input Validation is:
	
	- search functions
	- user-driven menu
	- accepts full state name or initials as input
	- accepts blank input
	- accepts any combination of capital letters
	- rejects strings with numbers
	
There were a total of 10 function implementations regarding the questions as requested by the instructor. The method to answer the questions was similar for most of the functions that we implemented.

The general logic for the Question Functions is:

	- function takes as parameter the dataframe
	- filter original datafram into a temporary dataframe containing information needed
	- works with the temp dataframe to obtain the answer
	- format the answer in a nice and clean way to print
		
In conclusion... 

	- 'pandas' is an amazing data science library
	- optimizing runtimes was more difficult than expected
	- there is a lot to consider for error handling
	- using a smaller data set can speed up testing]
		- drawbacks include lack of data to test
	- comments are very helpful in group project environments
	- communication can prevent merge conflicts
