# ML_Refinement
Machine Learning Refinement of the American College of Surgeons  NSQIP Risk Calculator

This analysis is focused on the Inpatient hospital mortality for high risk patients using The American College of Surgeons (ACS) National Surgical Quality Improvement Program (NSQIP) data for year 2012-2019. 

The American College of Surgeons National Surgical Quality Improvement Program database was queried for adult patients with a predicted mortality probability of 50% or greater as determined by the NSQIP calculator from 2012 to 2019. 

Machine learning algorithms were implemented and mortality  was modelled using stepwise logistic regression and Gradient boosting machines models. Following GBM modeling, the top five factors contributing to mortality were further explored using a local interpretable model-agnostic explanations (LIME) machine learning approach. LIME is an analytical technique to explain the predictions of a regressor by approximating it locally with an interpretable model.

All the date cleaning and prepr was performed in STATA, whereas modeling was performed using R Studio.

Access to NISQIP is subject to a Data Use Agreement and authorization by ACS NISQIP , all of the authors on this project have authorization to utilize this data set for research purposes.

We have made sure that all the analysis is thoroughly reviewed to be error free, furthermore all the results have been hidden that may lead back to tracing individual identiies. All the coding steps involved in linking, cleaning, and preparing the data for analysis and modeling have been listed below with the name of each file. Code for all steps involved in cleaning, linking, pre processing, propensity matching and modeling has been shared.
