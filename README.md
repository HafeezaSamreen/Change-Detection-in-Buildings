# Change-Detection-in-Buildings

The proposed model can be evaluated using various metrics, namely comparison of training and validation accuracy, F1 score, Precision, Recall, training and validation loss, Correlation matrix and determining the graph representation of building classification with various colours. Initially images of 1024*1024 pixels are cropped for better classification and after the images are cropped into square sized images, then the first output is obtained by segmentation and then final output is obtained by feature extraction. The model includes data pre-processing, Segmentation and Classification of buildings. Initially the “pre images and post images” are of 1024*1024 are taken and U-Net Architecture is used to determine the binary classification of buildings to determine whether the building exists or not and then ResNet50 architecture is used for multi classification of buildings as Vanishing, emerging and unchanged. Various colors’ labels are used to represent the buildings based on their existence in the post image. 
![image](https://github.com/HafeezaSamreen/Change-Detection-in-Buildings/assets/71244664/7b358587-464c-427e-a202-57f5f60ff7e8)
![image](https://github.com/HafeezaSamreen/Change-Detection-in-Buildings/assets/71244664/3b7fccfb-79f8-41fb-b77c-e66c0694c415)
![image](https://github.com/HafeezaSamreen/Change-Detection-in-Buildings/assets/71244664/7fdd461f-bab0-4bdd-b0fc-8b1bfffe78e1)
![image](https://github.com/HafeezaSamreen/Change-Detection-in-Buildings/assets/71244664/f9d1ee74-4f06-4a6e-ae7e-ec4a0979b2f9)

DATASET:
The XView Dataset is the forerunner to the xBD Dataset. It is one of the largest and most diversified where object detection datasets are accessible, with over 1 million items across 60 classes spread across 1400km2 of footage. The xBD dataset contains satellite images from various events, with a resolution of 1024*1024 and 22068 images and 850736 building polygons
Link to dataset: https://xview2.org/download
![image](https://github.com/HafeezaSamreen/Change-Detection-in-Buildings/assets/71244664/c6144060-4a9a-43bf-9ea5-f24a304b94d1)

RESULTS:
![image](https://github.com/HafeezaSamreen/Change-Detection-in-Buildings/assets/71244664/921a67bb-e1f9-47fd-b67b-6fe86488c7c2)





