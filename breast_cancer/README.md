## Breast Cancer: Project description
This folder contains files from a project as a part of Teknikhögskolan in Gothenburg, Sweden. The purpose of the project is to demonstrate skills in machine learning.

Here's what you'll find inside:

* breast_cancer.ipynb: Jupyter Notebook containing project code
* data set
* pickles models
* photos from the models, saved for presentation

## Models include in the study

* Support Vector Machines
* KNN
* Logistic Regression
* Random Forest
* Decision Tree
* LightGBM
* GBM
* AdaBoost 
* XGBoost
* CatBoost
* and Naive Bayes

## Technical specifications
The dependencies for the notebook are: Python 3.9, Matplotlib, Numpy, Pandas, Seaborn, Itertools, Pickle, Collections, Imbalanced-Learn, Scikit-Learn, XGBoost, LightGBM, Adaboost, and CatBoost
Because some models, i.e CatBoost, would have taken very long to run on my local machine, using Google Colab,  a GPU runtime will help to run. 
 In addition, the pickled models can be pretty large (>300MB), so if memory is an issue, you may want to skip over those cells.

## Source of data
This database is also available  the UW CS ftp server:
ftp ftp.cs.wisc.edu
cd math-prog/cpo-dataset/machine-learn/WDBC/
Also can be found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29 
Attribute Information:
1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:
* radius (mean of distances from center to points on the perimeter)
* texture (standard deviation of gray-scale values)
* perimeter
* area
* smoothness (local variation in radius lengths)
* compactness (perimeter^2 / area - 1.0)
* concavity (severity of concave portions of the contour)
* concave points (number of concave portions of the contour)
* symmetry
* fractal dimension ("coastline approximation" - 1)
 
The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.
* Missing attribute values: none
* Class distribution: 357 benign, 212 malignant
