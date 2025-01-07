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

## SVM Line
[Click to view](https://www.bing.com/images/search?view=detailV2&ccid=pnb7f28V&id=696EBE213D720FE7409892D8E2A13E870F3B1D29&thid=OIP.pnb7f28V2NKT3xTl61I0EAHaEF&mediaurl=https%3a%2f%2fvitalflux.com%2fwp-content%2fuploads%2f2022%2f08%2fsupport-vector-machine-1.png&cdnurl=https%3a%2f%2fth.bing.com%2fth%2fid%2fR.a676fb7f6f15d8d293df14e5eb523410%3frik%3dKR07D4c%252boeLYkg%26pid%3dImgRaw%26r%3d0&exph=484&expw=876&q=SVM+line&simid=607997985183576299&FORM=IRPRST&ck=2DAF641EFE58A99254E386E4DB191FA0&selectedIndex=4&itb=0)

[Maximum hyperplane, click](https://www.bing.com/images/search?view=detailV2&ccid=Fjj7EblD&id=A5579272CF8FDB0E4259BF5E825DEA5D78DEFC58&thid=OIP.Fjj7EblDs2J88GgJmyKL8wHaE8&mediaurl=https%3A%2F%2Fth.bing.com%2Fth%2Fid%2FR.1638fb11b943b3627cf068099b228bf3%3Frik%3DWPzeeF3qXYJevw%26riu%3Dhttp%253a%252f%252fwww.datasciencelovers.com%252fwp-content%252fuploads%252f2020%252f03%252fsupport-vector-machine-algorithm1.png%26ehk%3DsdIOvqkngF0qjtLudm6PaD9jAtBeNzB%252bu7w%252fbCkgP70%253d%26risl%3D%26pid%3DImgRaw%26r%3D0&exph=400&expw=600&q=maximum+margin+hyperplane&simid=607995889224129324&FORM=IRPRST&ck=A790BC1AA73A42AF318B654138A8B8D9&selectedIndex=23&itb=1&cw=1152&ch=534&ajaxhist=0&ajaxserp=0)

## Uniqueness of SVM
_SVM's unique combination of margin-based optimization, kernel flexibility, and support vector focus makes it distinct and effective for many challenging problems. However, its computational expense for large datasets and sensitivity to hyperparameters also set it apart as a tool requiring careful tuning._
