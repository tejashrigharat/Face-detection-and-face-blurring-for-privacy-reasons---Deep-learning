# Face-detection-and-face-blurring-for-privacy-reasons---Deep-learning
Face detection from images using MTCNN then designing and training the model. Using python to blur the detected faces in the images

* Create folders to save all the images wherever there is blank space left in the code and enter the path to the folder location
* All codes are in jupyter notebook file format. Install anaconda jupyter notebook to run all the files
* Preprocessing.ipynb does all the preprocessing on the data i.e. resizing and cropping of the images
  * MTCNN is used to prepare the data for training
  * The detected facial images are cropped and resized
* Train model.ipynb file sets the parameter for the convolutional neural network
  * The preprocessed facial images are used for the training of the CNN model
  * The trained CNN model is saved and evaluated
* BlurImages.ipynb file is used to blur the detected images and paste them back to the original picture
