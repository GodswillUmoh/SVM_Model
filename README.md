# SVM_Model

## Support Vector Machine (SVM) Overview
Support Vector Machine (SVM) is a supervised machine learning algorithm used for both classification and regression tasks. It is widely used for classification problems and works by finding the optimal hyperplane that best separates the data into classes.

## Key Concepts
### Hyperplane

> + In SVM, the hyperplane is a decision boundary that separates different classes.
> + For 2D data, it's a line; for 3D data, it's a plane; and for higher dimensions, it's a hyperplane.

### Support Vectors

> + These are the data points that are closest to the hyperplane.
> + They are critical in defining the position and orientation of the hyperplane.

### Margin

> + The margin is the distance between the hyperplane and the nearest data points from either class.
> + SVM maximizes this margin, aiming for better generalization.


## How SVM Works

### Linear SVM
_If the data is linearly separable, SVM finds the hyperplane that separates the classes with the maximum margin._

### Non-Linear SVM
_When the data is not linearly separable, SVM uses kernel functions to map data into a higher-dimensional space where a linear hyperplane can separate them._

