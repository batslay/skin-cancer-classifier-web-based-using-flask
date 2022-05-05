# skin-cancer-classifier
    Web based prototype skin cancer classification using CNN models that classifiying 7 class of skin cancer based on lesions skin condition.
    Made by : Ali Rohman (H1A018021) Teknik Elektro Universitas Jenderal Soedirman

This repository contains the machine learning models, I have also created flask web based UI for the classification prediction.

# Details about the files
    best_model_cutix.ipynb  :  iPythonNotebook File which classification of skin cancer based on the CNN model architecture that I made myself. 

    best_model_cutix.h5  : Weights are then saved to this file for directly used for UI purpose.

    app.py  : Flask based UI file which helps in prediction of the image by running the 'best_model_cutix.h5' file in the backend for making prediction by getting image by the user and predict the output.

    index.html  : For basic Interface of the webpage.

    main.css  : For styling the web interface.

    main.js  : To make websites more dynamic and interactive and to make file uploads more interactive on the web.

    uploads  : It contains the test image that uploaded byt users.


# Dataset 
    Link to download datasets : https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000 , https://www.kaggle.com/discdiver/mnist1000-with-one-image-folder (contains all images in 1 folder only)

# Required Libraries
    Web framework : Flask 
    Tensorflow
    Matplotlib
    Keras
    Numpy
    Pandas
    Scikit-learn

# Steps to do this project web based skin cancer classification using Visual Studio Code
     Step 1 : Run the ‘best_model_cutix.ipynb’ file using Google Colaboratory/Jupyter Notebook/Visual Studio Code
     Step 2 : At the final step of Training the model, save that model in the same folder in  which  the ‘app.py’ file.
     Step 3 : Set the path folder of saved Model in app.py.
     Step 4 : Now, run ‘app.py’ file to get the User Interface of Model Prediction (Classification)
     Step 5 : Follow the localhost link to open the User Interface in Web Browser and start to classify skin lesion conditions to know what types of skin cancer from the images that uploaded by users.
