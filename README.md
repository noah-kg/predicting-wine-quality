<div>
  <img src = "https://cf.ltkcdn.net/wine/images/orig/286294-2120x1414-red-wine.jpg" width = "800">
</div>

# Predicting Wine Quality Using Multiclass Classification Algorithms

In this project, I am to tackle the [wine data set](https://archive.ics.uci.edu/ml/datasets/wine+quality) from the UCI Machine Learning Repository. Though there are two sets of data (one for red wines and the other for white wines), this project will only focus on the red wine data set (for now). The dataset contains about 1,600 wines of varying qualities ranging from 0-10 (though they all fall within the 3-8 range). I aim to train and test multiple models to see which one can most accurately predict the wine's quality score. This data set is wildly imbalanced when it comes to quality, and that is a big hurdle I tackle in this project through the use of [SMOTE](https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.SMOTE.html).

## Project Goals:
* Exploratory Data Analysis
* Data Visualization of different compounds in wine
* Create pipeline structure to easily train/test multiple models
* Train/Test multiple models both before and after balancing out the data with SMOTE
* Use [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html) to assist in hyperparameter tuning of the top performing models

To view the notebook, click on the .ipynb file above, or view it [here](https://nbviewer.org/github/noah-kg/predicting-wine-quality/blob/main/Predicting%20Wine%20Quality.ipynb).
