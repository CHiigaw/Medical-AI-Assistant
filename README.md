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

To quickly get started with the AI Medical Assistant, follow these steps:

1. Clone the repository to your local machine.
2. If you have a Windows machine ensure you have [WSL (Windows Subsystem for Linux)](https://docs.microsoft.com/en-us/windows/wsl/install) installed if you haven't already. Open WSL and navigate to the directory where you cloned the repository.
3. Install python on wsl by running `sudo apt install python3 python3-pip`
4. Create a virtual environment in the directory by running `python3 -m venv <name>` in WSL. Replace `<name>` with the desired name for your virtual environment, we used venv as the name.
5. Activate the virtual environment by running `source <name>/bin/activate` in WSL. Replace `<name>` with the name of your virtual environment.
6. Install the required dependencies for the back-end using `pip3 install -r requirements.txt` within the activated virtual environment.
7. Install [Ollama](https://github.com/ollama/ollama) in WSL by following the installation instructions provided in the ollama repository or website. And pull a local model of your choice
8. Pull embedding of choice from ollama too. We used nomic-embed-text so we ran the command in wsl `ollama pull nomic-embed-text`
9. Set up the AI model by following the instructions in the `model` directory.
10. Start the back-end API by running `python app.py` within the activated virtual environment in WSL.
11. Open a new command prompt or PowerShell window in Windows (outside of WSL).
12. Navigate to the directory where you cloned the repository in Windows.
13. Install the required dependencies for the front-end using `npm install`.
14. Start the front-end development server using `npm start`.
15. Open a web browser and navigate to `http://localhost:3000` to access the application.
16. Type in a request in the chat interface and press enter to receive a response from the AI model.
17. To upload an image for diagnosis, click on the "Upload Image" button in the sidebar and select the image file.
18. The AI model will analyze the image and provide a diagnosis in the chat interface.

