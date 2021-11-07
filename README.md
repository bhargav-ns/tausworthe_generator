# tausworthe_generator
A custom tausworthe random number generator written in Python - System Simulation Project


- Directly run all cells in the .ipynb notebook to obtain the results.

- The 'tauseworthe' class in the notebook has all the methods defining a typical
tausworthe generator. There is also a static XOR function that simply 
implements the bit-wise XOR operation. 

- The input bits are all taken as strings. Bit addition is done as string appending.

- Run cell 3 to get a plot of the generated pseduo-random numbers on a unit square.

- The initial bits, r, and q can be modified when a new instance of the tauseworthe
class is created as shown in cells 3 and 4. Simply change the number of iterations
and the value of 'l' in order to generate more PRNs.

- Run the chi-squared goodness of fit test by running cell 6.

- Run the above and below mean test by running cell 7.

- Run the autocorrelation test by running cell 8.

- To generate normal variates from the PRNs, run cell 9.


Python ver. 3.7+
PACKAGES REQUIRED: scipy, numpy, tqdm, matplotlib, seaborn
