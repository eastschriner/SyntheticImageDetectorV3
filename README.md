# SyntheticImageDetectorV3
A Jupyter Notebook tool using a CNN to detect synthetic images.

This project is an image classifier that utilizes PyTorch to define and train a Convolutional Neural Network. This machine learning model can be used to make image classification predictions, either 'synthetic' (also known as 'AI-generated', 'Deepfaked', etc.) or 'real' (not generated). It has been trained off of a dataset of 20,000 images, and has 1000 images that have been used for assessing its prediction accuracy. A further 180 images have been set aside to be used as input files by the user (in the final codeblock). Other images may be examined by the model, but will require preprocessing to work properly. 

This tool is a primarily a demonstration of what CNNs are capable of; it is not currently capable of identifying synthetic pictures with total certainty. 

---

There are 2 .zip files available for download:

Synthetic_Image_Detector_Full.zip contains ALL files, including the 20,000 files used for training the model. Select this option if you wish to train the model or access the training files. 

Synthetic_Image_Detector_Light.zip omits the training files, resulting in reduced filesize and a much quicker download. This version doesn't allow training and will always load from the provided modelstate file. 

---


The dataset used in this project was taken from Kaggle, and can be found here:

[Kaggle CIFAKE Dataset](https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images)


---


The above dataset specifies that the following references must be included in any projects that use it:

Krizhevsky, A., & Hinton, G. (2009). Learning multiple layers of features from tiny images.

Bird, J.J. and Lotfi, A., 2024. CIFAKE: Image Classification and Explainable Identification of AI-Generated Synthetic Images. IEEE Access.

Real images are from Krizhevsky & Hinton (2009), fake images are from Bird & Lotfi (2024). The Bird & Lotfi study is available [here](https://ieeexplore.ieee.org/abstract/document/10409290.).


---


Sections of code have been adapted from or created while referencing the PyTorch 'Training a Classifier' tutorial, which uses the CIFAR10 database. The tutorial can be found here:

[PyTorch Classifier Tutorial]( https://docs.pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html)


---
