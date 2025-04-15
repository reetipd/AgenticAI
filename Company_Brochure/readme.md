# Company Brochure Generator

An AI-powered tool that automatically generates professional company brochures by analyzing company websites.

## Features

- Scrapes company websites to gather relevant information
- Identifies important links (About, Careers, Contact pages)
- Uses Llama 3.2 to generate professional company brochures
- Simple Gradio web interface

## Requirements

- Python 3.8+
- Ollama - for running Llama 3.2 locally
- Python packages: `requests`, `beautifulsoup4`, `openai`, `python-dotenv`, `ipython`, `gradio`

## Installation

1. Clone this repository
2. Install dependencies: `pip install requests beautifulsoup4 openai python-dotenv ipython gradio`
3. Install Ollama from [ollama.ai](https://ollama.ai/)
4. Pull the model: `ollama pull llama3.2`

## Usage

1. Run the Jupyter notebook (`company_brochure.ipynb`)
2. Enter the company name and URL in the Gradio interface
3. Click "Submit" to generate the brochure

## How It Works

1. Scrapes the company's landing page
2. Identifies relevant links using LLM analysis
3. Extracts content from important pages
4. Generates a professional brochure based on the content
5. Displays the formatted brochure in Markdown

