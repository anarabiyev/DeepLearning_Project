# DeepLearning_Project
This is Project Repo for Deep Learning subject

Team name: MedEnsemble
Member 1:  Anar Abiyev, W19RIG
Member 2:  Ramil Khalilli EV4EER

Task Description:

In this project, you'll dive into the idea of using multiple models together, known as model ensembles, to make our deep learning solutions more accurate. They are a reliable approach to improve accuracy of a deep learning solution for the added cost of running multiple networks. Using ensembles is a trick that's widely used by the winners of AI competitions. Task of the students: explore approaches to model ensemble construction for semantic segmentation, select a dataset (preferentially cardiac MRI segmentation, but others also allowed), find an open-source segmentation solution as a baseline for the selected dataset and test it. Train multiple models and construct an ensemble from them. Analyse the improvements, benefits and added costs of using an ensemble. 



<h1>Milestion 1<h1>
This notebook describes how to derive image pixel values from .nii files. The notebook consists of three parts:
* Loading Dataset: .nii files are loaded from corresponding folder path to the colab environment with the help of "nibabel" and "numpy" libraries.
* Visualization of Dataset: showing image - mask as pairs to express what the dataset looks like.
* Preprocessing: as each file contains several images, each channel is separated as individual frame. Then zero padding and resizing are applied to the images.
