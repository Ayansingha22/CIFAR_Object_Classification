# CIFAR_Object_Classification

There exists many methods to handle with the classification problems with machine learning and data mining. Three different classifier methods: K-Nearest Neighbors (KNN); Random Forest (RF); and Convolutional Neural Network (CNN) has been used for multiple classification of the real images dataset: CIFAR-10 dataset. In the pre-processing phase, Principal Component Analysis (PCA) is implemented to perform feature extraction for KNN and RF, in order to improve the efficiency and accuracy of these two classifiers. For the CNN, the convolutional filters used in each of layers has similar purpose as the PCA, but it projects the data onto a higher dimensional space rather than lower, to abstract the higher level features of images.Three methods are then evaluated and compared based on performance according to the specific metrics including accuracy, confusion matrix, cost-sensitive measure and computation runtime. After the evaluation, CNN outperforms the other models with much higher accuracy of more than 90% within 100 epochs.
