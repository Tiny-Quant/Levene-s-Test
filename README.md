# Levene-s-Test

Abstract: 
The goal of this code is to understand the robustness of Levene's Test for determining 
whether the variance between group is equal. The mechanics of Levene's Test are explained in
the Statistical Sleuth on page 103, but as a brief summary: Levene's Test compares the 
absolute deviations of each observation from their group median (Z). Then the means of each 
groups' Z values are compared. If there is no evidence of difference in the mean Z values, 
the variance of each group is assumed to be equal. The author of Sleuth claim that this test
is more robust than the F-test for equal variance and remains powerful even if the data is
non-normal. We will use simulation statistics to test the robustness of Levene's Test in 
the hopes of developing a streamline framework for checking the assumptions of ANOVA. 

Acknowledgement: 
I would to thank Dr. Charles South for his advice and suggests on this project. 


Status: In progress. 

References: 
Ramsey, F. L., &amp; Schafer, D. W. (2013). The statistical sleuth: A course in methods of 
data analysis. Brooks/Cole, Cengage Learning. 
