# Prism Coding Challenge

This Repository has been made to demonstrate my foundation solutions to the coding challenge assigned by Prism Analytics. 
The overall challenge has many parts to it, my understanding of the challenge is as follows:

1. Convert the data.txt file to five different .csv files based on Message type from the overall Tick Data - These files can be found as [Rdata.csv], [Qdata.csv], [Tdata.csv], [Sdata.csv], [Cdata.csv], this was particularly challenging for the quote data as the rows were misaligned in terms of the different field data (f4 and f12 data were found in the same row and therefore in the [Q.ipynb notebook] you can find a code explaining how I reshuffled this data back into the correct format), I manually inserted the column names as this was more time-efficient but could easily have been executed with python code.

2 & 3. Exercises 2 and 3 were done together in the same notebooks, [Exercises 2 and 3. ipynb] contains my first attempt at the challenge which was to manually create the database. However, this was proving to be time-consuming,
therefore you can find the final solution in the [New exercise 2 and 3. ipynb] file.

4. Exercise 4 is found in the [final exercise. ipynb]. While executing a solution, I was receiving an error suggesting that the 'Database was locked', therefore I created a new database named ['Ria.db']. There are two attempts at this solution, the first attempt was a successful algorithm, found at the start of the notebook, but this was not generating all the data in the 10-minute interval. I tackled this issue by adapting this code to show 100 rows of data before and after the row containing the inputted instrument code and time.

When running the notebooks, [New exercises 2 and 3. ipynb]  and the [final exercise. ipynb], ensure all the .csv files and [Ria.db] are in the same folder where the notebooks are contained so they are readable. 
