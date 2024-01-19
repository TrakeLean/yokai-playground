# Yokai Playground - ChatGPT API Testing

![ChatGPT API Status](https://img.shields.io/badge/ChatGPT%20API-Working-brightgreen)
![GitHub last commit](https://img.shields.io/github/last-commit/TrakeLean/yokai-playground)
![GitHub contributors](https://img.shields.io/github/contributors/TrakeLean/yokai-playground)
![GitHub top language](https://img.shields.io/github/languages/top/TrakeLean/yokai-playground)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/TrakeLean/yokai-playground)




## Overview

This project serves as a playground for testing ChatGPT API calls and integrating them into various applications. It offers a simple structure to initiate API requests, receive responses, and handle the conversation flow.

## Getting Started

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/TrakeLean/yokai-playground.git
    ```

2. **Install Dependencies:**
    ```bash
    cd yokai-playground
    pip install -r requirements.txt
    ```

3. **Setup .env**
    Make sure you are in the root folder of the project.

    - *Unix/Linux/Mac:*
        ```bash
        nano .env
        ```
        Write "API_KEY=your-api-key" and save.

    - *Windows:*
        ```bash
        echo .env
        echo API_KEY=your-api-key >> .env
        ```

4. **API Key:**
    Obtain your ChatGPT API key from [OpenAI](https://platform.openai.com/account/api-keys). Add the key to the .env file:
    ```plaintext
    API_KEY=your-api-key
    ```

*Github REPO:* [https://github.com/openai/openai-python](https://github.com/openai/openai-python)