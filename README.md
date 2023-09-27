# Sobriety-Period-Prediction-Using-Machine-Learning

This project is done with the real world data provided by SDM De-addiction and Research Centre,Ujire,India.


Purpose: To analyze the factors contributing to the relapse of persons with alcohol dependencies and predict their sobriety by considering male patient data from a De-addiction center. 

Design: To carry out this work,329 relapsed male patient’s data was collected through the case sheets and descriptive statistics; Bivariate and multivariate logistic regression was applied to determine the prominent factors associated with relapse and their correlation by the Pearson and Spearman correlation coefficients. The sobriety period of the patients taken as the class variable, but the number of patients in each class was varying. This class imbalance was overcome by using Synthetic Minority Oversampling Technique.

Findings: More than 92% (303) of patients were found to be relapsed once. Among the 303 patient records, the sobriety period of 33 patients was less than a 1 month, 28 in 1-3 months, 22 in 3-6 months, 36 in 6-9 months, 70 in 9-12 months and 114 in more than a year. Around 82.8% of patients were at very high risk, 8.91% at high risk,3.96% at medium risk and 4.29% at low risk of alcohol consumption. The risk factors for relapse were Craving (r=0.13, p=0.02) and peer pressure (r=0.137, p=0.016). The Factors for sobriety were found to be motivation factor (r=0.106, p=0.007), the influence of camp and willingness for treatment (r=0.05, p<0.05). Sobriety period predictive models were built using Gaussian NB, Random Forest and KNN. Gaussian NB outperformed with a sobriety period prediction accuracy of 98.68%.

Practical implication: Finding the probable sobriety period of patients is very important for planning treatment strategies to prevent their relapse after discharge. 
