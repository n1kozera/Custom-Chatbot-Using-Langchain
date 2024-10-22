# Custom-Chatbot-Using-Langchain
Custom Chatbot Using Langchain: Assignment from Triluxo Technologies Private Limited

This project demonstrates how to create a custom chatbot that extracts course data from a website, generates embeddings for the course descriptions, and provides a Flask RESTful API for user interaction. The chatbot is built using [Langchain](https://langchain.readthedocs.io/) and [Sentence Transformers](https://www.sbert.net/).

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Features
- Extracts course titles, descriptions, and prices from [Brainlox](https://brainlox.com/courses/category/technical).
- Generates embeddings for course descriptions using the Sentence Transformer model.
- Implements a Flask RESTful API to handle user queries.
- Provides a simple way to query the courses based on user input.

## Requirements
- Python 3.x
- Flask
- Langchain
- BeautifulSoup4
- Sentence Transformers
- FAISS (Facebook AI Similarity Search)

## Usage
- Run the Jupyter Notebook: Open the Jupyter Notebook file Chatbot.ipynb in your preferred environment (e.g., Jupyter Notebook, Google Colab) and execute the cells to set up and run the chatbot.
- Run the Python script: Alternatively, you can run the chatbot.py file directly in your terminal
- Make a POST request to the API: You can test the chatbot API using curl or tools like Postman

## File Structure
/repository-name
│
├── Chatbot.ipynb         # Jupyter Notebook with the implementation
├── chatbot.py            # Python script for the chatbot
└── README.md             # Project documentation

## Contributing
- Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
- This project is licensed under the MIT License - see the LICENSE file for details.
