This is the readme.md file for the Main Assignment Code. This file explains the processes done inside the main IPYNB file, Assignment_ML_Merged.ipynb

PART 0 - DATA PREPROCESSING(by Hannan)

- Loading Data : The dataset is read and loaded from a CSV file downloaded from Kaggle (Source : https://www.kaggle.com/code/salutonkielvifartas/students-mental-health-eda)
- Handling Missing Values : The dataset is checked for any missing values, such as NULL values. No missing values were found, so missing value handling methods were not required.
- Renaming Columns : Some columns were renamed to become more appropriate, consistent, and simpler, such as **HasMentalHealthSupport** to **Mental Support**, and the column values with lowercase such as **'year 4'** were capitalised to **'Year 4'**

PART 1 - EXPLORATORY DATA ANALYSIS(by Hannan)

- Displaying data in barcharts - For selected columns who are compatible, the amounts they have inside the dataset is displayed in barcharts. Example : Total number of male/females, Ages of all correspondents, YearOfStudy
- Displaying data counts - For columns that could not be displayed in barcharts due to compatibility issues, their counts are displayed in text form. Example : Course
- Creating bins - The CGPA's recorded in the dataset are split into bins, with a line showing the Kernel Density Estimate(KDE).
- Checking potential related columns - Picking a few columns, several EDA methods are used to chart/display these columns into multiple charts and text outputs. Example : Average stress level for each course with weighted averages, Depression levels for each year, Total Number of students receiving help vs not receiving help, if depression affects academic engagement
