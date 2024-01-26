### Documentation : retinal_image_classifier_app.py file

This file creates a web application that allows users to upload an image, and it uses a pre-trained Keras model to predict the class of the image. 
The prediction result is then returned to the user. The application is configured to run on a local server using Flask and gevent WSGI server (port 5000).
   - Initializes a Flask web application.
   - Defines the path to the pre-trained Keras model (MODEL_PATH).
   - Loads the model and prepares it for prediction.
   - Defines a function model_predict that takes an image path and a model as input.
   - Loads and preprocesses the image, then uses the model for prediction.
   - Defines two Flask routes:
     - '/': Renders the index.html template.
     - '/predict': Handles image uploads, calls the model_predict function, and returns the prediction result.
