# AI Email Generator

A simple tool that uses Llama 3.2 to generate professional emails based on user input.

## Features

- Generates complete emails including subject line and body
- Uses large language model (Llama 3.2) for natural-sounding content
- Customizable system and user prompts
- Works locally through Ollama

## Requirements

- Python 3.8+
- Ollama - for running Llama 3.2 locally
- Python packages: `openai`

## Installation

1. Clone this repository
2. Install dependencies: `pip install openai`
3. Install Ollama from [ollama.ai](https://ollama.ai/)
4. Pull the model: `ollama pull llama3.2`

## Usage

1. Run the Jupyter notebook (`email_generator.ipynb`)
2. Modify the `user_prompt` to include your specific information
3. Execute the cells to generate your email

## How It Works

1. Sets up system prompt to define the email context and format
2. Takes user input with relevant details
3. Sends both prompts to the Llama 3.2 model
4. Returns a complete, professional email
