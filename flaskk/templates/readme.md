**Documentation : basic.html**

  - This HTML file serves as a base template for other pages.
  - It includes the necessary Bootstrap and jQuery libraries.
  - The {% block content %}{% endblock %} allows other templates to extend this base template and override the content block.
  - It links the main CSS file for styling.

**Documentation : index.html**

  - Extends the basic.html template.
  - Contains the specific content block that includes the form for uploading images, the image preview section, and the result display.
  - Utilizes JavaScript from main.js for dynamic behavior.
