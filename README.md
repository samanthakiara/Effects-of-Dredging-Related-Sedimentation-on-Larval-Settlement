# Effects of Dredging-Related Sedimentation on Larval Settlement

data.csv: raw data used for statistical analysis in Thesis Code.Rmd

Thesis Code.Rmd: code for thesis work on the effects of dredging-related sedimentation on coral larvae

Thesis-Code.html: code with formatted output for easy viewing


This code includes data cleaning, and statistical analyses for each larval response (settled, partially metamorphosed, swimming, and dead).  For each larval response there is a series of model validation tests to determine the best model fit to the data, including a deviance goodness-of-fit test, and anova chi sq tests comparing full and reduced models, and with or without log transformed concentration.  Residual plots were used as a final checkpoint to determine the best model for each response.    

Model predictions were plotted for each larval response, and used to interpret the model summaries for each larval response to sediment (Table 6, Figure 6 in this thesis).  

Since there was a significant effect of sediment on larval settlement, and the model included log-transformed concentration, the model output was backtransformed to quanitfy the effect of a one-unit and ten-unit increase in sediment on larval settlement.  

Since the GLM for partial metamorphosis did not perform well, the raw data was plotted and interpreted instead (Figure 8).  

For swimming and mortality, there was no effect of sediment (p > 0.05).  

Table 3, 4, and 5 from this thesis were created in excel and used to generate Figure 4 and Figure 5.  Table 7 was created in excel and used to generate Figure 7.  


