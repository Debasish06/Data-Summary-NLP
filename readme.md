# Data Summarization Project

## Overview

This project implements a simple web-based application for data summarization using the Hugging Face BART model. Users can input text data through a web form, and the application will generate a summarized version of the input text.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [API Reference](#api-reference)

## Requirements

- Python 3.x
- Flask
- Hugging Face Transformers

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YourUsername/Data-Summarization.git
   cd Data-Summarization

## Usage
Run the application:
python app.py

Open your web browser and go to http://localhost:5000.

Enter your text data in the provided form and click "Submit" to get the summarized text.

## API Reference
The application provides an API endpoint for programmatic access to the summarization functionality.

Endpoint: /summarize
Method: POST