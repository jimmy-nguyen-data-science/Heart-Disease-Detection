# Heart Disease Detection Project

## Completed: 19 April 2021 

## Collaborators 
- Nava Roohi 
- Angela Zhang

## Project Objective
The purpose of this project is to assist health-care providers and physicians to increase the number of accurate heart disease diagnoses. The  problem for this project can be framed  as:

**Can data mining models be used to accurately predict and detect the presence of heart disease?**

## Project Background 
Heart disease has been responsible for millions of deaths each year among the world. In fact, health problems associated with the heart have become the leading cause of death in the past decades for both males and females. According to the Disease Control and Prevention Center, about 61,000 people die of heart disease in the United States annually that is 1 in every 4 deaths (Virani et al., 2020). Heart disease is one of the biggest concerns and having the capability to accurately detect heart disease would be extremely essential. Heart disease detection will be advantageous and insightful, so that health professionals can take the proper action ahead of time for earlier treatments leading to prevention (Wu et al., 2019). The information provided about the patients in this data set will pave the way for more accurate heart disease diagnosis. This is the leading motivation for investing time, effort, resources into developing these data mining models. 

### Methodology
- Obtaind data
- Define purpose 
- Determine data mining tasks
- Choose data mining algorithms
- Data Exploration
- Preprocess Data for Modeling
- Train and tune models 
- Evaluate performance
- Select final model
- Conclusion

### Technologies
- Python
- R-programming
- Powerpoint
- Word

## Data Mining Tasks
The purpose of this project is to utilize the information about each patient to accurately classify the presence of heart disease. Since the target variable is a binary data type with 0s and 1s, this is a binary classification problem that prioritizes positive cases. Therefore, accuracy is not an important metric, instead it should be precision and recall. However, it is best to combine both precision and recall as one single measure called the harmonic mean, where recall weighs half as much as precision(Tan et al., 2020). The reason why is because precision describes the measure of patients correctly predicted as having a heart disease out of all patients who do have it. So the best metric is to compute a harmonic mean where B = 0.5. Thus, the data mining model that has the best harmonic mean score where B = 0.5 would therefore perform better than the rest.

## Data Mining Algorithms
- Gaussian Naive Bayesian
- Logistic Regression
- Random Forests


## Presentations and Reports
* [Final Report](https://github.com/Jimmy-Nguyen-Data-Science-Portfolio/Flu-Vaccines-Prediction/blob/main/Report/Flu%20Vaccines%20Prediction%20-%20Data%20Analysis%20Report.pdf)
* [Presentation Slides](https://github.com/Jimmy-Nguyen-Data-Science-Portfolio/Flu-Vaccines-Prediction/blob/main/Presentation/Final%20Presentation%20-%20Jimmy%20Nguyen.pdf)
* [Python Code](https://github.com/Jimmy-Nguyen-Data-Science-Portfolio/Flu-Vaccines-Prediction/blob/main/Presentation/Final%20Presentation%20-%20Jimmy%20Nguyen.pdf)
* [R-programming Code](https://github.com/Jimmy-Nguyen-Data-Science-Portfolio/Flu-Vaccines-Prediction/blob/main/Presentation/Final%20Presentation%20-%20Jimmy%20Nguyen.pdf)


## Data Visualizations
![Survey Responses](https://github.com/Jimmy-Nguyen-Data-Science-Portfolio/Flu-Vaccines-Prediction/blob/main/Data%20Visuals/Beh.%20Questions.png)

![Vaccine Concerns about Effects](https://github.com/Jimmy-Nguyen-Data-Science-Portfolio/Flu-Vaccines-Prediction/blob/main/Data%20Visuals/H1N1%20Con%20vs%20Vac.png)

![Vaccine Recommendations based on Gender](https://github.com/Jimmy-Nguyen-Data-Science-Portfolio/Flu-Vaccines-Prediction/blob/main/Data%20Visuals/Vaccine%20Recommendations.png)


## Original Data 
[UCI Machine Learning Repository - Heart Disease Data Set](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)

## References
Larose, C. D., & Larose, D. T. (2019). Data science using Python and R. Wiley. (2019).

Tan, P.-N., Steinbach, M., Karpatne, A., & Kumar, V. (2020). Introduction to data mining.       
Pearson. 

Virani, S., Alonso, A., Benjamin, E., S. Bittencourt , M.,  Callaway, C., Carson, A., &     
Chamberlain, A. (2020, January 29). Heart Disease and Stroke Statistics— 2020 Update. Circulations. https://www.ahajournals.org/doi/10.1161/CIR.0000000000000757 

Wu, C.-seh, Badshah, M., & Bhagwat, V. (2019, July). Heart Disease Prediction Using Data 
Mining Techniques. https://dl.acm.org/doi/10.1145/3352411.3352413. https://dl-acm-org.sandiego.idm.oclc.org/doi/pdf/10.1145/3352411.3352413 



