## Maintenance - Failure Prediction Project

This project is a maintenance error prediction project. In the project, a CSV file containing maintenance data is used as the data source. Data preprocessing steps include checking for missing or outlier values, and removing some columns after the check.

Visualization libraries are used to produce meaningful results and analysis through visualization. 

### Failure Distribution

![failure-dist](https://github.com/RumeysaHilal/Machine-Learning-Projects/assets/66912242/e3bfcc0f-4e8e-43a5-bebc-737409add407)

### Heatmap

![heatmap](https://github.com/RumeysaHilal/Machine-Learning-Projects/assets/66912242/4f6c36c9-3c4a-40c7-997d-b1d4db2bd3b0)

### Proportion of the Types attribute
![proportion-types](https://github.com/RumeysaHilal/Machine-Learning-Projects/assets/66912242/e8f7e088-e80c-4bcf-80f8-98336b4152d6)


### PCA Method
PCA (Principal Component Analysis), also known as factor analysis, is a method used to examine relationships between variables in a multidimensional dataset and to reduce the dimensionality of the dataset. PCA transforms a dataset into a set of principal components by using the correlations between variables in the dataset. These principal components retain the most information about variability in the dataset.

This graph demonstrated that the first four features could be utilized as principal components.

![pca-explained](https://github.com/RumeysaHilal/Machine-Learning-Projects/assets/66912242/52a2f8dc-d749-4880-a75e-5928d50b276e)

### GridSearchCV and Pipeline Structure
The effectiveness of models and the cleanliness of the code structure are improved using a pipeline structure. To find the best model, the GridSearchCV method was used. 

![gridsearch](https://github.com/RumeysaHilal/Machine-Learning-Projects/assets/66912242/d6a34481-6feb-4e4e-ad68-bc95e2c2de84)

 The best performing model is saved using the pickle method, and deployment is accomplished using the Streamlit library.

![failure-pred](https://github.com/RumeysaHilal/Machine-Learning-Projects/assets/66912242/2f03ad69-8236-42c1-b187-ca9a9e3d22e6)
