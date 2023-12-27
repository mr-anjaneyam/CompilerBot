# Python Compiler Telegram Bot

This repository contains a Telegram bot built with Python that acts as a Python compiler. 
The bot allows users to send Python code snippets or files and receive the corresponding output or error messages.

## Features

- Accepts Python code as text
- Compiles and executes the code
- Captures and displays standard output and error messages
- Handles dynamic user inputs during code execution
- Provides real-time feedback through Telegram messages

## Usage

1. Start the bot by sending the `/start` command.
2. To compile code, send the code snippet.
3. Send the Python code you want to compile as text or upload a file containing the code.
4. The bot will execute the code and send back the output or error message.
5. If the code prompts for user input, the bot will ask for the input dynamically.
6. Provide the input in the chat, and the bot will continue executing the code.
7. The bot can handle multiple user inputs as required by the code.

## Requirements

- Python 3.x
- Python-telegram-bot library (`pip install python-telegram-bot`)

## Setup

1. Clone this repository.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Obtain a Telegram bot token from [BotFather](https://core.telegram.org/bots#3-how-do-i-create-a-bot).
4. Replace `"your_token_here"` with your actual Telegram bot token in the code.
5. Run the `pyCompiler.py` script to start the bot.
6. Interact with the bot through the Telegram chat.

## Contributions

Contributions to this project are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.
