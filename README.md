# Facial-Expression-Recognition
A machine learning model developed through the integration of Principal Component Analysis, unsupervised learning K-means, and supervised learning Support Vector Machine. This model is able to categorise facial expression into seven classes: angry, disgust, fear, happy, neutral, sad, and surprise.

Training and test data were obtained from ‘Kaggle’. It is a platform where it offers
access to a variety of datasets, many of which are freely available for public use. The link to
the datasets is; https://www.kaggle.com/datasets/msambare/fer2013?select=test

HOW TO USE: 
- The file "subfile - Test with small sample" is used for image categorisation purpose. Use google collab to run this code.

- Upload (kmean.pkl, nonlinear_svm_model.pkl, pca_modelall265.pkl, X_train_pca.pkl, y_train.pkl) to google collab. 

- All images to be categorised is loacated in ONE folder in google drive. Let's say the folder name is INPUTFOLDER.

- The code in the file have a line of code to access image data from google drive folder, edit this address so that the code can access the correct file. The address must be pointing to a folder1 in which there is another one folder (INPUTFOLDER) that contains all images. for example: test_data_dir = '/content/drive/My Drive/Colab Notebooks/folder1'

- Finally run the code, and the output will be the images labeled with respective categorised emotion.


OTHER FILE PURPOSES:

- "MainFile - machine learning" : a file that evaluates the overall categorisation of the machine learning model. This file is also used to get the machine learning model pkl files (kmean.pkl, nonlinear_svm_model.pkl)

- "Subfile - PCA and Supervised model evaluation" : a file to preprocess training and testing image data from 'Kaggle' using PCA, for further training and testing purposes. (to get pca_modelall265.pkl, X_train_pca.pkl, y_train.pkl, X_test_pca.pkl, y_test.pkl)

This is a group project made by our team: Noorul Ghousiah; Nurain Ainaa Aqilah
