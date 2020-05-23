# Classification using Convolutional Neuron Network from scratches

## Folder structure
```
.
├── Content
|   ├── Test_image
|   ├── image_class
|   ├── CNN.model
|   ├── buildnetwork.ipynb
|   ├── model.h
|   ├── model.json
|   ├── X.pickle
|   └── y.pickle
└── Output
    └── output_image


```

The **Content file** contains all the necessary folder, packages and codes required for the implementation of the model
- Image_class contains the image folder consisting all classes required for training  
- Test_image consist of the images used for testing 
- model.h is the model generated from training the CNN network
- model.json consist the configuration of the model
- X.pickle store the features of the image
- y.pickle store the labels of the features
- buildnetwork.ipynb consist of the complete code for the classification model

The **Output file** consists of a copy of the results obtained from the evaluation process. The results obtained is in the following format:
- image



## Description of the model

The dataset consisted of 6 classes 
- art studio
- auditorium
- bakery
- bar
- bedroom
- bathroom

The sequential model designed consisted of 3 convolutional layers, 2 hidden layers and 1 output layer with 6 neurons with activation function set to softmax. 
Each class consisted of 100 images each with the split ratio of 10:90 and the data the data was trained for 40 epochs and batch size set as 32. The optimizer selected was "adam" and categorical crossentropy was  loss metric since the output is classification of multiple classes.

The model was trained on  540 samples and 60 validation sample.
The final model was tested on a test images and the it showed a decent results

![](https://raw.githubusercontent.com/osman-95/Project_Prog/master/ReadMe_img/Capture4.PNG)










