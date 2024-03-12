# CarClasTxt (Car Classification by Textetion)
### member
- Salute Khumyunn 6410450273
- Phollaphat Soisermsup 6410450184
- Tanapat Bumrungthaiworakul 6410451016
---
## application
- [anaconda](https://www.anaconda.com/download)

## items
- CarClassification.ipynb: notebook file that contain building model code for this project
- resource: folder for put the image dataset here separate by wheels type 4, 6, and 6+ in each folders
- sample resorce: the link that you can download the resource dataset files

## module & library
*Please set environment and install these modules before run the building model*
*If the module not working, please try reinstall the modules. If still not working, try change the package manager between pip or conda to install modules*
- os
- jupyter notebook: ```pip install notebook```
- tensorflow: ```pip install tensorflow```
- cv2: ```pip install opencv-python```
- h5py: ```pip install h5py```
- numpy: ```pip install numpy```
- keras: ```pip install keras```
- sklearn: ```pip install -U scikit-learn```
- matplotlib: ```pip install matplotlib```

## pre-trained model
- RestNet50 model

---
# Instruction

## setup instruction
- First prepare resource of image dataset. You can download from the sample resource link(or this [link](https://drive.google.com/file/d/14MejCuwe8cwr9ZEtuUg2t-uylZnPpN5Y/view?usp=sharing)), and put them in resource folder for each type.
- Open CarClassification.ipynb.
- now you can start the building code.

## building instruction
- first import the module and library into the notebook.
- load and preprocess the dataset. with 3 categories 4 wheels, 6 wheels, and 6 wheels+.
- make imageDataGenerator for build model.
- make label of output of images in list. 0 as 4 wheels, 1 as 6wheels, and 2 as 6wheels+.
- shuffle and split data for train and validation test. with default of the code we using 70% for train and 30% for vaidation test.
- apply the datagen into the dataset
- import pre-trained RestNet50 model to make transfered learning and build the model after load the pre-trained model.
- train the model 
- observe the result. you can observe loss and accuracy with plot that we implemented

## save & load model instruction
at the bottom of the code you can save the trained model for next prediction. also you can load model to use prediction
