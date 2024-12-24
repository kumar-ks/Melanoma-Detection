# Melanoma Detection Assignment
> This project is focused on building a machine learning model to classify skin cancer types using images. The goal is to create a system that can assist healthcare professionals in identifying and classifying skin cancer from images, improving diagnosis accuracy and reducing the time taken for initial assessments.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- This project utilizes a convolutional neural network (CNN) to classify skin cancer images into different categories.
- The business problem is to assist in automating the diagnosis of skin cancer, providing healthcare professionals with a reliable tool to aid in early detection and improve the accuracy of diagnoses.
- The dataset being used is a collection of labeled images from a skin cancer dataset that includes various types of skin lesions. The dataset has been augmented to handle class imbalance.

## Technologies Used
- TensorFlow - version 2.7.0
- Keras - version 2.7.0
- Augmentor - version 0.2.7
- Matplotlib - version 3.4.3
- NumPy - version 1.21.2
- Pandas - version 1.3.3
  
## Conclusions
- The model was able to significantly improve training accuracy, but validation accuracy was still lower, indicating potential overfitting.
- Data augmentation and class balancing techniques improved the diversity of the training data.
- Dropout layers and regularization techniques helped in reducing overfitting to some extent.
- More tuning of hyperparameters and model architecture may be necessary to improve generalization and accuracy on the validation dataset.