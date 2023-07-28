**NeuroNet: Deep Learning for Brain MRI Tumor Classification**


I have designed the NeuroNet model to classify brain tumors from MRI scans utilizing the VGG19 model pre-trained on the ImageNet dataset. The VGG19 model is a robust deep learning model, which has a top-5 test accuracy exceeding 90% on ImageNet's cross validation set. I have trained and fine-tuned my model on a comprehensive dataset of over 5700 MRI scans derived from figshare, SARTAJ, and Br35H. I have also used Keras Fine Tuner, adjustments to VGG19 layers, and Dense and Dropout layers to optimize my model's performance. As a result, my model was able to **achieve an accuracy of 97.7% on the test set**, which is unseen data.


This project is an application of the deep learning theory and techniques I have learned. The dataset can be seen here: https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset?select=Training. I have trained my model to classify 4 classes: giloma, meningioma, no tumor and pituitary. Here are some of the test set predictions below!


<img width="1058" alt="image" src="https://github.com/Ari1029/NeuroNet/assets/45503218/aa29dd4b-e206-4521-a928-44b7a4f80d8f">



