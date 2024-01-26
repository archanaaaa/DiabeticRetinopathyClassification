# Diabtic Retinopathy Classification 

### Documentation : retino.ipynb

This code aims to build and train a convolutional neural network (CNN) using the Keras library for the purpose of classifying diabetic retinopathy levels from retinal images. It involves preprocessing image and label data, partitioning it into training and validation sets, creating a CNN model, training the model with augmented data, saving the trained model, and generating plots to visualize the training process. Additionally, it includes functionality to load the trained model and make predictions on the training data. The ultimate goal is to develop an effective deep learning model for accurate diabetic retinopathy classification.

The code utilizes several key libraries for various tasks:
  - cv2 (OpenCV): Employed for image processing tasks, such as resizing images.
  - matplotlib: Used for creating plots and visualizing images.
  - keras: A high-level neural networks API, used for building and training the convolutional neural network (CNN) model.
  - scikit-learn (sklearn): Utilized for machine learning tasks, specifically for splitting data into training and validation sets.
  - Flask: A web framework used for serving machine learning models.
  - gevent: A library for asynchronous programming, used in combination with Flask for handling web requests.
