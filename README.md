# DNN-Architectures-for-Defect-Detection

In this project, we developed a model to detect defects by Industrial Optical Inspection on Textured Surfaces. This problem can be modelled as an Image Segmentation task where we had to find the pixels where the defect occurs in a given image.
The dataset we will be using is described here:
https://hci.iwr.uni-heidelberg.de/node/3616
There are many ways to solve this problem.We will attempt to solve this using deep learning and the approach we will follow is based on the paper on U-Net: Convolutional Networks for Biomedical Image Segmentation.

The project will be done using a high-level library Keras. Although Keras is not very flexible and hence not the preferred choice for most people, it is easy to understand.
Since the project requires training deep networks, you will be requiring a GPU. To facilitate this, the project will be done using Google Colab. Google Colab provides free GPU runtime and can be synced with Google Drive to transfer/load data.
Steps:
1. Save the dataset in your Google Drive.
Go to this link and click the “Add to My Drive” button on the top right.
The dataset will be visible in the root folder of your Google drive after a few seconds.
2. Go to http://colab.research.google.com/ and upload the .ipynb file provided in this project.
3. Set the Runtime to GPU from the menu on the top left.
