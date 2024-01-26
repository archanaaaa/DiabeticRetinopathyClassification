Documentation : main.js  

  - The JavaScript code uses jQuery to handle user interactions and make asynchronous requests to the Flask server.
  - It initializes the page by hiding certain elements like the image section, loader, and result.
  - The readURL function displays a preview of the uploaded image.
  - The $('#imageUpload').change event is triggered when an image is selected for upload, revealing the image section and predict button.
  - The $('#btn-predict').click event is triggered when the predict button is clicked, initiating an AJAX request to the Flask server's /predict endpoint. The loader is displayed during this process.
  - Upon success, the prediction result is displayed.
