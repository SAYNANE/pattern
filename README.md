This code used to print the pattern G.
If we try to analyze this picture with a (row, column) matrix and the circles represent the position of stars in the pattern G, we will learn the steps. Here we are performing the operations column-wise. 
So for the first line of stars, we set the first if condition, where the row position with 0 and (n-1) won’t get the stars and all other rows from 1 to (n-1), will get the stars. 
Similarly, for the second, third and fourth column we want stars at the position row = 0 and row = (n-1). 
The other steps are self-explanatory and can be understood from the position of rows and columns in the diagram.
