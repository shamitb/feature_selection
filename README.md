# Feature Selection for Machine Learning
Python Methods for Feature Selection

----------------------------

- Univariate Selection

Statistical tests can be used to select those features that have the strongest relationship with the output variable.
The scikit-learn library provides the SelectKBest 

-----------------------------------------------------------------

- Feature Extraction with PCA - Principal Component Analysis

Principal Component Analysis (or PCA) uses linear algebra to transform the dataset into a compressed form.
Generally this is called a data reduction technique. 
A property of PCA is that you can choose the number of dimensions or principal component in the transformed result.

------------------------------------------------------------------

- Bagged decision trees like Random Forest and Extra Trees 
These can be used to estimate the importance of features.
In the example below we construct a ExtraTreesClassifier classifier for the Pima Indians onset of diabetes dataset. 
You can learn more about the ExtraTreesClassifier class in the scikit-learn API.

--------------------------------------------------

- The Recursive Feature Elimination (or RFE) 
This works by recursively removing attributes and building a model on those attributes that remain.
It uses the model accuracy to identify which attributes (and combination of attributes) contribute 
the most to predicting the target attribute.
You can learn more about the RFE class in the scikit-learn documentation:
http://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.RFE.html#sklearn.feature_selection.RFE
