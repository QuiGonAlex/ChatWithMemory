# Chat with Memory

## Description
The Chat with Memory application is an interactive Jupyter notebook designed to facilitate local, private conversations with various Large Language Models (LLMs). It is tailored for open-source, free-to-use, and customizable LLMs, providing a secure environment as it operates entirely locally. The standout feature of this application is its memory structure, which enhances the quality of user interactions over time by remembering past conversations and context.

## Key Features
- **Local Chat with LLMs**: Chat securely with multiple open-source LLMs without the need for external servers.
- **Privacy**: Everything runs locally on your machine, ensuring that your data remains private.
- **Memory-Enhanced Interactions**: Utilizes a memory structure to improve interaction quality by remembering and learning from previous dialogues.
- **Customization**: The choice of the LLMs is adjustable and supports modified and custom models as well.

## Installation
To set up and use this application, follow these detailed steps:

### Install Visual Studio Code
1. If not already installed, download Visual Studio Code from [https://code.visualstudio.com/](https://code.visualstudio.com/).
2. Install the Python extension for VSCode from the marketplace.

### Install Jupyter
1. Install Jupyter using the integrated terminal in VSCode or your system's command line: `pip install notebook`.

### Install Ollama
1. Ollama is necessary for this application. Install Ollama by either:
   - Downloading it directly from [https://ollama.com/](https://ollama.com/), or
   - Using the command line: `pip install ollama`

### Download and Open the Notebook
1. Download the `ChatWithMemory.ipynb` file to your local machine.
2. Open VSCode, navigate to the `File` menu, select `Open File`, and open the downloaded notebook.
3. VSCode should recognize the notebook and provide an interface for running the cells.

## Usage
This application is interactive:
1. Follow the instructions within the notebook to initiate conversations with the configured LLMs.
2. Chat with the LLMs at the bottom of the notebook, and the program will remember the context of your interactions, storing the the conversations for subsequent interactions.

## Extending the Application
- **Custom LLMs**: Instructions for integrating additional open-source and even modified/customized LLMs are included within the notebook.
