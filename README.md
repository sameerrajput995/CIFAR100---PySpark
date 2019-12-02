# CIFAR100---PySpark
Performed binary classification using PySpark

The CIFAR-100 dataset has 100 classes containing 600 images each. There are 500 training images and 100 testing images per class. The 100 classes in the CIFAR-100 are grouped into 20 super classes. Each image comes with a "fine" label (the class to which it belongs) and a"coarse" label (the superclass to which it belongs).

The project is divided into 2 parts - Milestone 1 and Milestone 2

Milestone 1 - The goal is to perform a binary classification of images in vehicle 1 and vehicle 2 superclass pairs using PySpark.

Milestone 2 - Classify images not seen by the model during training. 
Prediction on one testing subclass images from each of the two superclasses. Select one sub-class from each of your two assigned super-classes. Use these two selected sub-classes as your testing data. Use all the data minus the two selected test sub-classes as your training data. Repeat for all 5 x 5 =25 pairs of subclass images. Your algorithm should be initialized before it is being trained on new training dataset in each of these 25 trials. All results should be based on the SAME algorithm you designed.
