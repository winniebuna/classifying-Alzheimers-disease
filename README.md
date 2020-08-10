# classifying-Alzheimers-disease
**CLASSIFYING ALZHEIMER'S DISEASE FROM BRAIM MRI SCANS USING DEEP NEURAL NETWORKS**
»this is a neural network that uses VG19, a CNN architecture to classify Alzheimer's disease patients from from healthy patients using their brain images

**STEPS TO FOLLOW**
1. Software Requirements
  the system that was used was Windows 10 with 64-bit Operating System and the language used was Python programming Language
  -Anaconda
  -Jupyter Notebook
  -Matplotlib
  -TensorFlow
  -Keras
2. Hardware Requirements
  the minimum hardware that i recommend for this project are
   -HP EliteBook Folio 9480m
   -Intel Core i7 4600U Processor
   -14 inch Full HD Screen
   -8GB Ram
   -256GB SSD
3. Data Preparation
  ImageDataGenerator class provided by tf.Keras were used to perform the following operations:
  -Format the Images into appropriately preprocessed floating point tensors before feeding to the model
  -Read images from the disk 
  -Decode contents of these images and convert it into proper grid format as per their RGB content
  -Convert them into floating point tensors
  -Rescale the tensors from values between 0 and 255 to values between 0 and 1
  -Set up the generator taht convery these images into batches of tensors when training the model
  -After defining the generators for training the generator for training and validating images, the flow_from_directory method load images from the disk, applies rescaling, 
    and resizes the images into the required dimensions.


»link to the dataset that was used can be found here
https://www.kaggle.com/tourist55/alzheimers-dataset-4-class-of-images
