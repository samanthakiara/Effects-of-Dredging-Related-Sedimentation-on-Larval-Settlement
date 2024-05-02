# Effects of Dredging-Related Sedimentation on Larval Settlement

Code for thesis work on the effects of dredging-related sedimentation on coral larvae

This code includes data cleaning, and statistical analyses for each larval response (settled, partially metamorphosed, swimming, and dead).  For each larval response there is a series of model validation tests to determine the best model fit to the data, including a deviance goodness-of-fit test, and anova chi sq tests comparing full and reduced models, and with or without log transformed concentration.  Residual plots were used as a final checkpoint to determine the best model for each response.    

Model predictions were plotted for each larval response, and used to interpret larval response to sediment.  

Since there was a significant effect of sediment on larval settlement, and the model included log-transformed concentration, the model output was backtransformed to quanitfy the effect of a one-unit and ten-unit increase in sediment on larval settlement.  

Since the GLM for partial metamorphosis did not perform well, the raw data was plotted and interpreted instead.  

For swimming and mortality, there was no effect of sediment (p > 0.05).  

Figure 4, 5 and 7 from this thesis were created in excel.  
