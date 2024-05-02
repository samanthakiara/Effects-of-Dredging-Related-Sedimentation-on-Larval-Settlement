# Effects of Dredging-Related Sedimentation on Larval Settlement

data.csv: raw data used for statistical analysis in Code.Rmd

Code.Rmd: code for thesis work on the effects of dredging-related sedimentation on coral larvae

Output.html: code with formatted output based on Code.Rmd for easy viewing


This code includes data cleaning, and statistical analyses for each larval response (settled, partially metamorphosed, swimming, and dead).  For each larval response there is a series of model validation tests to determine the best model fit to the data, including a deviance goodness-of-fit test, and anova chi sq tests comparing full and reduced models, and with or without log transformed concentration.  Residual plots were used as a final checkpoint to determine the best model for each response.    

Model predictions were plotted for each larval response, and used to interpret the model summaries for each larval response to sediment (Table 6, Figure 6 in this thesis).  

Since the GLM for partial metamorphosis did not perform well, the raw data was plotted and interpreted instead (Figure 8).  

Table 3, 4, and 5 from this thesis were created in excel and used to generate Figure 4 and Figure 5.  Table 7 was created in excel and used to generate Figure 7.  


