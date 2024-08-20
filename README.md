# AI-CHEMIST

This project is a Streamlit web application that uses Google's Generative AI (Gemini) to analyze images of pharmaceutical tablets. Here's the workflow:

1. Setup and Imports:
   - The code imports necessary libraries and loads environment variables.
   - It configures the Google Generative AI with an API key.

2. Helper Functions:
   - `get_gemini_response`: Sends requests to the Gemini AI model and retrieves responses.
   - `input_image_setup`: Prepares uploaded images for processing by the AI model.

3. User Interface (Streamlit):
   - Creates a web interface with a title, input field, and file uploader.
   - Allows users to input text and upload an image.

4. Image Processing:
   - When an image is uploaded, it's displayed in the app.

5. AI Interaction:
   - When the user clicks "Tell me":
     a. The uploaded image is processed using `input_image_setup`.
     b. The prepared image, user input, and a predefined prompt are sent to the Gemini model.
     c. The AI analyzes the image and generates a response.

6. Result Display:
   - The AI's response is displayed on the web page.

The core functionality revolves around analyzing pharmaceutical tablets in images. The AI is prompted to:
1. Identify the tablets in the image.
2. Describe each tablet's uses and functions.
3. Provide information on their purposes and applications.
4. Note any distinguishing characteristics.
5. Give clear, concise descriptions focusing on key details.

This application bridges pharmacy expertise with AI capabilities, offering quick, detailed analyses of pharmaceutical tablets from images.
