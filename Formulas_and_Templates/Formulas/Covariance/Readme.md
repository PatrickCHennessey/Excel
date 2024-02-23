Excel/LIL/Learning_Excel_Data_Analysis/Ex_Files_Learning_Excel_Data_Analysis/Exercise Files/Chapter05/

*Note: GitHub Repository Path (contains the original unsolved file(s).)*:


**Single Covariance** 

Covariance : =(A2-AVERAGE($A$2:$A$11))*(B2-AVERAGE($B$2:$B$11))

Covariance.P : =COVARIANCE.P((A2:A11),(B2:B11))

Covariance.S : =COVARIANCE.S((A2:A11),(B2:B11))

*Note: Covariance.P function is used in Population calculations.*
*Note: Covariance.S function is used in Sample calculations.*


**Multiple Covariance**

Cell G2 : =COVARIANCE.S($A$2:$A$11,A2:A11)

Cell G3 : =COVARIANCE.S($B$2:$B$11,A2:A11)

Cell G4 : =COVARIANCE.S($C$2:$C$11,A2:A11)

Cell G5 : =COVARIANCE.S($D$2:$D$11,A2:A11)

Select G2 through G4 and drag to right to obtain H, I, and J values.