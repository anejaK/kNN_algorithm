# k Nearest Neighbour from scratch
## Implemenation
**mainFunction()**
The MainFunction performs all the functionalities from Importing the dataset to
calculating the accuracy in which all these operations are being called individually, For
Examples Importing the dataset, in which the dataset are imported and the values are
being stored as training values and testing values in lists. The explanations of these

**findNearestClass()**
This function is used to find the appropriate class nearest to the instance testData. This is
determined by the specific function named calculateDistance.

**CalculateDistance()**
Here, the euclidean distance is being calculated between two points (testInstance and
the value wanted to be predicted) for each nearest K points. Once the distances are
calculated it is stored in the distance List and the values are being sorted in order to find
the nearest neighbour of that instance. 

**getResponse()**
This function is used to rank the classes accordingly by the distance which was
calculated and sorted previously. This predicts the testValues in finding the right class by
the ranks(count).

The algorithm is tested on Breast cancer Dataset
**Accuracy Achieved - 89% - 90%**


