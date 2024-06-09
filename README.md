# Gemini-pro-
Extracting Invoice Info
-Below I'm writing all the steps in sequence way, please go through it:
## 1. Python Programming Language:
The primary language used for developing the application.
## 2. Streamlit:
A framework for building and deploying web applications quickly and easily using Python.
Used for creating the web interface of the Invoice Extractor, including file upload functionality and displaying results.
## 3. Google Generative AI (Gemini Model):
Utilized for generating responses based on the input invoice image and prompt.
Requires knowledge of configuring and interfacing with the API provided by Google.
## 4. Pillow (PIL):
A Python Imaging Library used for opening, manipulating, and saving image files.
Employed to handle the uploaded image file and display it in the Streamlit app.
## 5. Google Generative AI API:
An API provided by Google to access their generative AI models.
The GenerativeModel from the google.generativeai library is used to interact with the Gemini model.
## 6. dotenv:
A Python package used to read key-value pairs from a .env file and set them as environment variables.
Useful for managing sensitive information like API keys securely.
## 7. File Handling and Bytes Manipulation:
Reading the uploaded image file and converting it into a format suitable for processing by the AI model.
## 8. Image Processing:
Basic handling of images, including uploading, displaying, and preparing them for AI model input.
## 9. API Integration:
Interfacing with external APIs (in this case, Google's Generative AI API) to utilize advanced machine learning models.
