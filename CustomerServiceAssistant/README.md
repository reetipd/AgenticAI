# Airline Customer Service Assistant

A Jupyter notebook implementation of an AI-powered airline customer service assistant that helps customers check flight ticket prices using natural language queries.

## Features

- Interactive chat interface using Gradio
- Uses Llama 3.2 model through Ollama (local model deployment)
- Function calling capabilities to retrieve flight ticket prices
- Conversational memory that maintains chat history

## Dependencies

- Python 3.11+
- Jupyter Notebook
- OpenAI Python client library
- Gradio
- Ollama (with Llama 3.2 model)

## Setup

1. Install the required dependencies:
   ```
   pip install jupyter openai gradio
   ```

2. Install Ollama from [https://ollama.com/](https://ollama.com/)

3. Pull the Llama 3.2 model:
   ```
   ollama pull llama3.2
   ```

4. Run the Jupyter notebook:
   ```
   jupyter notebook customer_service.ipynb
   ```

## Usage

After running the notebook, a Gradio interface will be launched. You can interact with the assistant by:

1. Asking about flight ticket prices to different destinations (e.g., "How much is a flight to London?")
2. The assistant will provide the ticket price if the destination is in its database
3. For unknown destinations, the assistant will inform you that the price is unknown

