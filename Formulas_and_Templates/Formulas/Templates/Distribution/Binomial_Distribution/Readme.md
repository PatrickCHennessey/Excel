Note: GitHub Repository Path (contains the original unsolved file.):
Excel/LIL/Learning_Excel_Data_Analysis/Ex_Files_Learning_Excel_Data_Analysis/Exercise Files/Chapter04/04_05_Binomial.xlsx


Binomial Distribution - Deals with trials where there are only two outcomes. An example being customer signs up for the company mailing list or doesn't.

To Determine the Likelihood of a Specific Number of Customers Signing Up.

1. Percentage of Outcomes (cell B5): =BINOM.DIST(A5,$B$2,$B$1,FALSE)


To Determine the Probability of a Specific Number of Succeses or Less

1. Percentage of Outcomes: =BINOM.DIST(A5,$B$2,$B$1,TRUE)