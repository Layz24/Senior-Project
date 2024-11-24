# SeniorProject
# AI Chatbot Interaction Script

This repository contains a Python script designed for interacting with OpenAI's API to manage chatbot conversations. It uses threads to handle messages and streamline interactions between the user and an AI assistant.

## Features

- Initializes an AI chatbot.
- Handles user input to create and manage threads.
- Utilizes OpenAI's API for generating AI responses.
- Processes and retrieves message histories for conversations.
- Leverages external training data to enrich chatbot responses.
- **Easily updateable knowledge base**: Add new information to the `training_data.txt` file for the chatbot to learn more.

## Prerequisites

To run this script, you need:

- Python 3.8 or higher.
- OpenAI Python client library (`openai`).
- A valid OpenAI API key.

## Setup

1. Clone the repository or download the script file.
2. Install the required library:
   ```bash
   pip install openai
   
## APIKEY
client = OpenAI(api_key="your_api_key_here")


## Usage
response = message("What are the requirements for a computer science degree?")
print(response)

