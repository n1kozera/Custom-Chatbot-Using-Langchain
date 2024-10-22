# Custom-Chatbot-Using-Langchain
Custom Chatbot Using Langchain: Assignment from Triluxo Technologies Private Limited

This project demonstrates how to create a custom chatbot that extracts course data from a website, generates embeddings for the course descriptions, and provides a Flask RESTful API for user interaction. The chatbot is built using [Langchain](https://langchain.readthedocs.io/) and [Sentence Transformers](https://www.sbert.net/).

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
