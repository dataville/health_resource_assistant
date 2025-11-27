# AI Agents Capstone Project - Health Resource Assistant

A health resource assistant AI agent built using Google's Agent Development Kit (ADK) and Gemini API. The agent searches through a FAQ knowledge base to answer health-related questions about topics like free flu shots, Medicaid providers, mental health resources, and emergency services.

## Features

- FAQ knowledge base with categorized health information (general health, mental health, emergency services)
- MCP (Model Context Protocol) toolset integration for file search capabilities  
- Interactive testing interface with conversation history
- Automated evaluation framework with scoring metrics
- Performance visualization and analysis

## Requirements

- Google Gemini API key
- Python packages: `google-adk`, `google-genai`, `mcp`

## Setup

1. **Get your Gemini API key**
   - Create an API key at [Google AI Studio](https://aistudio.google.com/app/api-keys)

2. **Install dependencies**
   ```bash
   pip install -q google-adk google-genai mcp
   ```

3. **Configure authentication**
   - Set your API key as an environment variable `GOOGLE_API_KEY`

## Usage

The notebook contains a complete implementation including:

- FAQ knowledge base creation with health resource information
- AI agent configuration using Google's Agent Development Kit
- Interactive testing interface for asking health-related questions
- Automated evaluation system with scoring metrics

## Project Structure

- Creates `/tmp/faq-knowledge/faqs` directory for FAQ storage
- Implements categorized health FAQs (general health, mental health, emergency services)
- Uses MCP toolset for file search capabilities
- Includes performance evaluation and visualization

## Author

[Charles Rice](http://www.datainference.ai)

## License

Licensed under the Apache License, Version 2.0