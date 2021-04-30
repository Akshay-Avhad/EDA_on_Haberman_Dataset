# EDA_on_Haberman_Dataset

*Introduction:*

The Haberman Dataset consists of the data recorded between the year 1958 to 1970 at the University of Chicago's Billing Hospital. The dataset indicates the survival of the patients after surgery who are detected with breast cancer.

*Methodology Used:* Exploratory Data Analysis

*Tools Used for Analysis:* Python(Jupyter Notebook)

*The Variables in the dataset are:*
1) Age (Age of patient at time of operation)
2) Year (Patient's year of operation)
3) Nodes (Number of positive axillary nodes detected)
4) Status (Survival status)

*Packages Used:*
1) Pandas
2) Numpy
3) Matplotlib
4) Seaborn

*Data Visualization:*

![](https://github.com/Akshay-Avhad/EDA_on_Haberman_Dataset/blob/main/Visualisations/Haberman%20EDA%202.PNG)


*Conclusion:*
1) Majority of the data is overlapping which does not clearly guide us in determining which factor is the best in helping us to classify status 1 and status 2 patients.
2) We observed that if number of nodes are greater than 10, there is a very high chance of the patient being of status 2.
3) We can slightly observe that operations that were done relatively earlier have more status 2 patients. This may be because of unavaible medical advancements which might have been made in the future, But the difference observed is small.
4) Age of a person does not indicate clearly the possibility of their survival status.
5) So order of importance of features would be Nodes >  Year > Age.
