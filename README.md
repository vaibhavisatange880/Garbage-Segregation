How to implement the models?
->Download the dataset and upload it in your drive.
->Use Google Colab Notebook,select runtime as T4 GPU as it will fasten the training process.
->Mount the drive,split the dataset ,here I have split it into 70:15:15 as train:test:val
->Import required libraries and packages.
->Implement the algorithms for the number of epochs you want.
->Test the model via prefications.

For YOLO,you will require dataset.yaml file which contains the paths to train,test and val folder and the labels of categories you have.
For our project we have used labels as 0 for cloth,1 for Glass,2 for Paper and 3 for Plastic.
For VGG implementation,no need of yaml file.
Output video and images are attached in zip file of outputs.
