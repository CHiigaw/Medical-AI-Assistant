# AI Medical Assistant

## Overview

The AI Medical Assistant is a web-based application designed to provide medical advice and diagnoses using artificial intelligence. The application features a chat interface similar to Mistral or ChatGPT, where users can type in their requests and receive responses from the AI model. Additionally, the application includes a sidebar on the left where users can upload images to be used for diagnosis.

## Features

- Chat interface for user requests and AI responses
- Image upload functionality for diagnosis
- AI model trained on medical data for accurate diagnoses and advice
- User-friendly interface built with React
- Back-end API built with Flask

## Environment Information

The AI Medical Assistant is built using the following technologies:

- Python 3.10.12
- crewAI
- llama index 0.10.36
- Flask web framework
- TensorFlow/PyTorch machine learning library
- React for the front-end

## Quickstart

To get started with the AI Medical Assistant, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies for the back-end using `pip install -r requirements.txt`.
3. Install [Ollama](https://github.com/ollama/ollama) and pull a local model (we used llama3)
4. Set up the AI model by following the instructions in the `model` directory.
5. Start the back-end API using `python app.py`.
6. Install the required dependencies for the front-end using `npm install`.
7. Start the front-end development server using `npm start`.
8. Open a web browser and navigate to `http://localhost:3000` to access the application.
9. Type in a request in the chat interface and press enter to receive a response from the AI model.
10. To upload an image for diagnosis, click on the "Upload Image" button in the sidebar and select the image file.
11. The AI model will analyze the image and provide a diagnosis in the chat interface.
