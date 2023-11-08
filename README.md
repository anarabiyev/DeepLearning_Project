# DeepLearning_Project
This is Project Repo for Deep Learning subject

Team name: MedEnsemble
Member 1:  Anar Abiyev, W19RIG
Member 2:  Ramil Khalilli EV4EER

Task Description:

In this project, you'll dive into the idea of using multiple models together, known as model ensembles, to make our deep learning solutions more accurate. They are a reliable approach to improve accuracy of a deep learning solution for the added cost of running multiple networks. Using ensembles is a trick that's widely used by the winners of AI competitions. Task of the students: explore approaches to model ensemble construction for semantic segmentation, select a dataset (preferentially cardiac MRI segmentation, but others also allowed), find an open-source segmentation solution as a baseline for the selected dataset and test it. Train multiple models and construct an ensemble from them. Analyse the improvements, benefits and added costs of using an ensemble. 



# DeepLearningProject_M1.ipynb

This notebook describes how to derive image pixel values from .nii files. The notebook consists of three parts:
* Loading Dataset: .nii files are loaded from corresponding folder path to the colab environment with the help of "nibabel" and "numpy" libraries.
* Visualization of Dataset: showing image - mask as pairs to express what the dataset looks like.
* Preprocessing: as each file contains several images, each channel is separated as individual frame. Then zero padding and resizing are applied to the images.


# DeepLearningProject_M2.ipynb

This notebook represents trainging and testing phases of the model. 
Prior to them, the prepared datasets are loaded as numpy arrays from drive folder. 

<h2>UNet model</h2>
As UNet is one of the mostly used model architectures for segmentation tasks, it has been used here. The encoder and decoder part are built using functions of tensorflow keras. 

<h2>Evaluation</h2>
During evaluation, both train and test sets have been predicted using model weights. 
Firstly, the results have been randomly showen to check the predicted masks. 
Then, Diec Coefficent score which is widely used for segmentation evaluation, has been calculated for sample in train and test sets. 
The results are shown in histogram and in average.
