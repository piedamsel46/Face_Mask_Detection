# Face_Mask_Detection

Face_Mask_Detection
Directory Structure and description of content:

dataset - (Train test splits are taken from this dataset) -cloth (Cloth Mask Images) -N95 (N95 Mask Images) -no (No Mask Images) -surgical (Surgical Mask Images) -N95 with valve (N95 with valve)

link for dataset- https://drive.google.com/file/d/1iepC-ZlHd5R9Sq-q0X6DPkQSwN1pzouH/view?usp=sharing

testDataset (directory consisting sample images for prediction) -random

FinalMasksCNN.ipynb - Jupyter Notebook consisting of all the code

FinalModelFDCNN.pkl - Convolutional Neural Network model saved after training.

Steps to run the notebook:

Skip the first cell that has the code to load the existing model, if running for the first time. After training and saving the model, you can visit the first cell to load the model and head to the last cell to predict on random images by replacing "output = face_mask_detector_cnn(inputs)" with "output = modelTrained(inputs)" as shown in report.
