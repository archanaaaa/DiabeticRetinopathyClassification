# Diabtic Retinopathy Classification with Flask

### Table of Contents

1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Usage](#usage)
   - [Setting Up the Environment](#setting-up-the-environment)
   - [Running the Application](#running-the-application)
   - [Using the Web App](#using-the-web-app)
4. [Model Details : retino.ipynb](#model-details)

### 1. Introduction<a name="introduction"></a>

This project is a web application developed with Flask for the classification of diabetic retinopathy based on retinal images. The application allows users to upload retinal images and receive predictions about the severity of diabetic retinopathy.

### 2. Project Structure<a name="project-structure"></a>

The project structure includes the following key components:

- **`retinal_image_classifier_app.py`**: The main Python script containing the Flask application, model loading, and prediction functions.
- **`uploads`**: Directory to store uploaded retinal images.
- **`templates`**: Directory containing HTML templates for the web application.

### 3. Usage<a name="usage"></a>

#### Setting Up the Environment<a name="setting-up-the-environment"></a>

1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd <project-directory>`
3. Create a virtual environment (optional but recommended): `python -m venv venv`
4. Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On Unix or MacOS: `source venv/bin/activate`
5. Install required packages: `pip install -r requirements.txt`

#### Running the Application<a name="running-the-application"></a>

Run the Flask application using the following command:

```bash
python retinal_image_classifier_app.py 
```

The application will be accessible at [http://127.0.0.1:5000/](http://127.0.0.1:5000/).

#### Using the Web App<a name="using-the-web-app"></a>

1. Open your web browser and go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/).
2. Upload a retinal image using the provided form.
3. Click the "Predict level" button to initiate the classification.
4. View the predicted result on the web page.

### 4. Model Details : retino.ipynb <a name="model-details"></a>

This code aims to build and train a convolutional neural network (CNN) using the Keras library for the purpose of classifying diabetic retinopathy levels from retinal images. It involves preprocessing image and label data, partitioning it into training and validation sets, creating a CNN model, training the model with augmented data, saving the trained model, and generating plots to visualize the training process. Additionally, it includes functionality to load the trained model and make predictions on the training data. The ultimate goal is to develop an effective deep learning model for accurate diabetic retinopathy classification.

The code utilizes several key libraries for various tasks:
  - cv2 (OpenCV): Employed for image processing tasks, such as resizing images.
  - matplotlib: Used for creating plots and visualizing images.
  - keras: A high-level neural networks API, used for building and training the convolutional neural network (CNN) model.
  - scikit-learn (sklearn): Utilized for machine learning tasks, specifically for splitting data into training and validation sets.
  - Flask: A web framework used for serving machine learning models.
  - gevent: A library for asynchronous programming, used in combination with Flask for handling web requests.
