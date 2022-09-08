Directory Structure and description of content:

dataset - (Train test splits are taken from this dataset)
	-cloth (Cloth Mask  Images)
	-N95 (N95 Mask  Images)
	-no (No Mask  Images)
	-surgical (Surgical Mask  Images)
	-N95 with valve (N95 with valve)

link for dataset- https://drive.google.com/drive/folders/16kavL1e4v0WENa0HcPO6n3UG5mctPMhs?usp=sharing

testDataset (directory consisting sample images for prediction)
	-random

FinalMasksCNN.ipynb - Jupyter Notebook consisting of all the code

FinalModelFDCNN.pkl - Convolutional Neural Network model saved after training.

Report part 1 - Report file consisting details and statistics of the project.

Steps to run the notebook:

Skip the first cell that has the code to load the existing model, if running for the first time. 
After training and saving the model, you can visit the first cell to load the model and head to the last cell to predict on random images by replacing "output = face_mask_detector_cnn(inputs)" 
with "output = modelTrained(inputs)" as shown in report.