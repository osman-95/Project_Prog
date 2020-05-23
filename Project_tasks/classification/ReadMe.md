# Classification using Mobilenetv2

## Folder structure
```
.
├── Content
|   ├── image_class
|   ├── saved_model
|   ├── tflite_models
|   ├── classify_pract.ipynb
|   └── ...
└── Output
    └── images


```

The **Content file** contains all the necessary folder, packages and codes required for the implementation of the model
- It contains the image folder required for training and evaluation 
- tflite file containing the code and tflite model generated from the saved model
- The folder that saves checkpoints of the training
- classify_pract.ipynb consist of the complete code for the classification model

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

Each class consisted of 100 images each with the split ratio of 20:80 and the data the data was trained for 10 epochs setting the optimizer as "adam" and loss metric as categorical crossentropy since the output is classification of multiple classes.

The model was trained for 15 steps and validated for 4 steps. The model trained is saved in **saved_model file**  to use it as an initial pretrained model for later training to improve the accuracy and reduce computation time.

The final model was tested on a test images and the it showed a decent results

![](https://raw.githubusercontent.com/osman-95/Project_Prog/master/ReadMe_img/Capture3.PNG)









