# PCA and K-means clustering on the Breast Cancer Wisconsin data set


## Ross Erskine, Ho Him Lee
![varianceExplained](https://user-images.githubusercontent.com/46631932/236257096-ecce23c7-9edf-4456-a549-a55c8aa3059e.png)

Variance explained describes the variance from the principle components, which states that with six components, we can describe 90% of the data.

## Abstract
Breast cancer is a common disease for middle-aged women. For this project, we focus on discovering the possibilities to perform features engineering on a breast cancer dataset collected by wolberg(1990) at the University of Wisconsin-Madison Hospital. This dataset contains 699 instances with 9 features and two classes, benign and malignant. Two features engineering method are used in this project, the first one is Principal component analysis which aims to reduce the dimension of the features. The second method we used is K-means Clustering to simulate the two classes in the dataset.

## Data:
The data for the Breast Tumours is available from the ML respository of UC Irvine
https://archive.ics.uci.edu/ml/datasets.php
under
Breast Cancer Wisconsin (Original)

## Results
PCA aim is to simplify the data, which creates a new coordinate system by altering the data linearly. fig. 2 depicts principle component with n = 2 with Different colours used for benign and malignant, however, some points are obscured and found not to be completely seperated, although in fig. 3 shows principle component with n = 3 and the separation is slightly better. PCA is explained by separating the data into nth variations in the data. 1 depicts that variance by, explaining that 90% of the data can be explained with six of the features from the data set, which is in line with other research such as
[19], although, [7] claimed that 2 principle components accounted for 37.5% of the data we managed 73.982%, and [14].
In this research, we performed a K-means cluster algorithm, on the breast cancer Wisconsin data using K= 2 to simulate the two classes, benign and malignant. fig. 4 Shows the two clusters separated by two different colours and Two centroids depicted in the center of each cluster.We then compared our clusters with the original classification from the data.


![PCA_2](https://user-images.githubusercontent.com/46631932/236258750-2468b296-6372-4060-a679-086c4d58bc75.png)

![PCA_3](https://user-images.githubusercontent.com/46631932/236259501-f14982ae-8239-4b50-96c8-ccb90cc9943f.png)

![K-means](https://user-images.githubusercontent.com/46631932/236259570-2c6c31ae-61c0-48c7-9d8d-d2aef8b9196c.png)




