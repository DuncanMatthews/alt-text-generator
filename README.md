# Image Alt Text Generator

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

This Jupyter Notebook allows you to generate alternative text (alt text) for images based on a CSV file. Alt text is essential for making images accessible to visually impaired users who rely on screen readers and for improving the searchability of images on the web.

## Features

- Load a CSV file containing image URLs
- Generate alt text for each image using Google's Vision AI
- Save the generated alt text back to the CSV file

## Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab
- Required Python packages: `pandas`, `requests`, `google-api-python-client`
- google.generativeai as genai


## Setup

1. Clone the repository: git https://github.com/DuncanMatthews/alt-text-generator
2. Install the required Python packages: pip install pandas requests google-api-python-client
3. Set up a Google Cloud Platform project and enable the Vision AI API.
4. Obtain your API key and configure it in the notebook:
5. import genai

genai.configure(api_key='YOUR_API_KEY')
   

Copy code
# Image Alt Text Generator

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

This Jupyter Notebook allows you to generate alternative text (alt text) for images based on a CSV file. Alt text is essential for making images accessible to visually impaired users who rely on screen readers and for improving the searchability of images on the web.

## Features

- Load a CSV file containing image URLs
- Generate alt text for each image using Google's Vision AI
- Save the generated alt text back to the CSV file

## Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab
- Required Python packages: `pandas`, `requests`, `google-api-python-client`
- Google Cloud Platform account with Vision AI API enabled

## Setup

1. Clone the repository:
git clone https://github.com/your-username/alt-text-generator.git
2. Install the required Python packages:
pip install pandas requests google-api-python-client
3. Set up a Google Cloud Platform project and enable the Vision AI API.
4. Obtain your API key and configure it in the notebook:


genai.configure(api_key='YOUR_API_KEY')
Replace 'YOUR_API_KEY' with your actual API key.

## Usage

Prepare your CSV file with an image_url column containing the URLs of the images.
Open the Jupyter Notebook file alt_text_generator.ipynb.
Run the notebook cells in sequential order:
Load the CSV file into a pandas DataFrame
Generate alt text for each image URL using the Vision AI API
Save the generated alt text back to the CSV file
CSV File Format
The CSV file should have the following format:



