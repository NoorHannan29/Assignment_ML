# Executive Summary

(note, pls less than 300 words cuz guidelines)

Mental health in Malaysia has always been overlooked, especially in younger generations. With this dataset, it contains various mental health from university students. This can be used as research on the effect of mental health on university students' CGPA. It was provided by Jia Jun Chen on the Kaggle site (https://www.kaggle.com/datasets/junnn0126/university-students-mental-health).

The project was started off by Hannan with data preprocessing. This includes the process of loading the data, handling missing values, and renaming columns. Then EDA was performed, which includes the process of displaying data in barcharts, as well as data counts, creating bins, and checking potential related columns.

Next is the PCA process conducted by Khoo. More data preparation is performed on the dataset for the PCA process, and then PCA was performed after. Analysis was then made on the PCA process, which reveals that PCA may not be needed for this project.

After that, Wan Muhammad Atif developed a Random Forest model to predict the possibility of student having anxiety based on selected features like sleep quality, study stress, and academic engagement. A new interaction feature combining study hours and sleep quality was introduced. The data was split, standardized, and balanced using class weights. GridSearchCV optimized hyperparameters, and the best model was evaluated with a confusion matrix and classification report. Feature importance analysis identified key predictors, providing insights into factors influencing student anxiety.
