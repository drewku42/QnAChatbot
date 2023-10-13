# Question Answer Bot Demo
## Overview
Welcome to the Question Answer Bot Demo repository! This project is an interactive chatbot designed to answer questions based on the contents of uploaded PDF or text files. Using specialized text splitters and loaders, the bot processes uploaded documents into manageable chunks. These chunks are then transformed into embeddings via OpenAI's API and stored for quick retrieval. When a question is asked, the chatbot uses these embeddings and the OpenAI API to provide precise answers, making it a powerful tool for extracting and discussing information from text-based files.

## Features
File Upload: Accepts PDF and text files for processing.
Text Splitting: Splits the uploaded documents into manageable chunks for easier processing.
Text Embedding: Utilizes OpenAI's API to generate embeddings for the text.
Question Answering: Uses the embeddings to answer user queries about the uploaded documents.
Source Attribution: Provides the source of the answer from the uploaded documents.

## Installation
### Requirements
- Python 3.x
- OpenAI API key

### Steps
1. Clone the repository:
git clone https://github.com/drewku42/QnAChatbot.git

2. Navigate to the project directory:

3. Install the required packages: langchain, chainlit, dotenv

4. Create a .env file to store your OpenAI API key:
- OPENAI_API_KEY = your_openai_api_key_here

5. Run the application:
- chainlit run document_qa.py

### Usage
- Start the chatbot to receive the welcome message.
- Upload a PDF or text file as prompted.
- Wait for the file to be processed.
- Ask questions about the content of the uploaded file.

Acknowledgements
OpenAI for their API and embeddings.
All contributors are welcome!
Enjoy using the Question Answer Bot Demo!
