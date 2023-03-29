# Retinal-OCT-eye-disease-prediction

Retinal optical coherence tomography (OCT) is an imaging technique used to capture high-resolution cross sections of the retinas of living patients. Approximately 30 million OCT scans are performed each year, and the analysis and interpretation of these images takes up a significant amount of time
 
## Dataset
category (NORMAL,CNV,DME,DRUSEN). There are 84,495 X-Ray images (JPEG) and 4 categories (NORMAL,CNV,DME,DRUSEN).

Images are labeled as (disease)-(randomized patient ID)-(image number by this patient) and split into 4 directories: CNV, DME, DRUSEN, and NORMAL.

Check out the dataset [here](https://www.kaggle.com/paultimothymooney/kermany2018)

## Model
The model is a CNN model with 4 convolutional layers and 2 dense layers. The model is trained on 80% of the dataset and tested on the remaining 20% of the dataset. The model is trained for 10 epochs and the accuracy is 96.5% on the test set.

Run the model on your Google colab[here](https://colab.research.google.com)

##Steps to run
Generate your kaggle auth key from [Kaggle](https://www.kaggle.com/) and upload that to the colab environment.

## Results
The model is able to predict the disease with an accuracy of 96.5% on the test set.
