# Object based Environment Classification
**NOTE-** The documentation is not completely updated.

The main aim of the project is to design a real time environment recognition using object detection. the classitfication of the environment class is determined by the objects detected in the image/Frame.

The work was borken into the following structure

1. **Research**
2. **Data selection and preprocessing**
3. **Understanding and Testing of the Algorithm(pretrained models)**
4. **implementation of Desired Data with the desired Algorithm**
5. **Testing and evaluation of the Project output**

Before Elaboring the above sections a quick overview on the file hierarchy is shown below
- Understanding_concept
  - Mobilenetv2
  - YoloV3 ()
  - YoloV3 ()
  - classification_model_1 ()
  - classification_model_2 ()
  
- Implemnetation_Final_Model
  - **_Currently under progress_**
  
## Research
After the research done so far the two pretrained Models were chosen to perform object detection in realtime
- Yolo V3
- Mobilenet V3

From the above catergories of algorithm two yolo v3 models from github were selected to be tested on the sample data as shown in the folder hierarchy. One Mobilenet v2 model was used from tensorflow API model lists.

Currently going through this [paper](http://vision.stanford.edu/pdf/Fei-Fei_Li_ICVSS09_bookchapter.pdf) to detemine an algorithm to predict or classify a frame from the object list of the detected object.


## Data selection and preprocessing
The dataset was selected from [Kaggle](https://www.kaggle.com/itsahmad/indoor-scenes-cvpr-2019?) provided by MIT. It consists of  67 categories/classes and a total of 15620 images of indoor scenes. The number of images varies across categories, but there are at least 100 images per category and All images are in jpg format.

Only 6 categories were chosen to work on due to the time and Hardware limitations. 

The sample Data consisted of only one class "Kitchen" with selection of only 300 images was used to test the Pretrained moedl before executing the main dataset.
