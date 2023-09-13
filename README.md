# Give_caption_and_detect_objects_from_image
This is a Stream lit application that allows users to ask questions about an uploaded image and receive responses from a conversational AI agent. The agent uses the OpenAI GPT-3.5 Turbo model to generate answers based on the provided image and user input.

## installation
        
1. Install the required dependencies:

        pip install -r requirements.txt

2. Replace the API key in the main.py file with your actual OpenAI API key:

            openai_api_key='YOUR_API_KEY',

3. Run main.py and after that run the Streamlit application by writing this command in command propmt:

        streamlit run main.py

4. It will automattically Open your web browser if not open this link in your browser

	http://localhost:8501/



## tools

The application utilizes the following custom tools:

- **ImageCaptionTool**: Generates a textual caption for the uploaded image.
- **ObjectDetectionTool**: Performs object detection on the uploaded image and identifies the objects present.

## usage

1. Upload an image by clicking the file upload button.

2. The uploaded image will be displayed.

3. Enter a question about the image in the text input field.

4. The conversational AI agent will generate a response based on the provided question and image.

5. The response will be displayed below the question input.
