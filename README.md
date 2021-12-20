# Heart Disease Detection Project

## Completed: 19 April 2021 

## Authors and Collaborators
- [Jimmy Nguyen](https://github.com/jimmy-nguyen-data-science)
- Nava Roohi 
- Angela Zhang


## Installation

Data Exploration and Modeling was all done in [Jupyter Notebook](https://jupyter.org/).

To clone this repository onto your device, use the commands below:

	1. git init
	2. git clone git@github.com:jimmy-nguyen-data-science/Heart-Disease-Detection.git

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
* [Final Report](https://github.com/Jimmy-Nguyen-Data-Science/Heart-Disease-Detection/blob/main/Report/Project%20Report.pdf)
* [Presentation Slides](https://github.com/Jimmy-Nguyen-Data-Science/Heart-Disease-Detection/blob/main/Presentation/Project%20Presentation.pdf)
* [Python Code](https://github.com/Jimmy-Nguyen-Data-Science/Heart-Disease-Detection/blob/main/Code/Python%20Jupyter%20Notebook/Python%20Jupyter%20Notebook.pdf)
* [R-programming Code](https://github.com/Jimmy-Nguyen-Data-Science/Heart-Disease-Detection/blob/main/Code/R%20code/Data%20Exploration%20-%20R.pdf)


## Data Visualizations
![Age Groups](https://github.com/Jimmy-Nguyen-Data-Science/Heart-Disease-Detection/blob/main/Data%20Visuals/Age%20Groups.png)

![Age Groups vs Resting Blood Pressure](https://github.com/Jimmy-Nguyen-Data-Science/Heart-Disease-Detection/blob/main/Data%20Visuals/Age%20Groups%20vs%20Resting%20Blood%20Pressure.png)

![Sex vs Heart Disease](https://github.com/Jimmy-Nguyen-Data-Science/Heart-Disease-Detection/blob/main/Data%20Visuals/Sex%20vs.%20Heart%20Disease.png)


## Performance Results

![Performance Table](https://github.com/Jimmy-Nguyen-Data-Science/Heart-Disease-Detection/blob/main/Data%20Visuals/Evaluation%20of%20Models.png)

![k-Folds Cross-Validation Table](https://github.com/Jimmy-Nguyen-Data-Science/Heart-Disease-Detection/blob/main/Data%20Visuals/K-folds%20Cross%20Validation%20Table.png)

![ROC-AUC Curves](https://github.com/Jimmy-Nguyen-Data-Science/Heart-Disease-Detection/blob/main/Data%20Visuals/ROC%20AUC%20Curves.png)


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



