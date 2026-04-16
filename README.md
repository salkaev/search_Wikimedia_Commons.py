# Wikimedia Commons Image Downloader

A Python script that searches for and downloads images from Wikimedia Commons via the official MediaWiki API.

## Features

- Search Wikimedia Commons by keyword
- Automatically downloads the top matching image
- Handles API rate limits with proper User-Agent header
- Saves files with correct extensions (jpg, png, svg, etc.)

## Requirements

- Python 3.6+
- `requests` library

## Installation
bash
# Clone the repository
git clone https://github.com/salkaev/search_Wikimedia_Commons.py.git
cd search_Wikimedia_Commons.py

# Install dependencies
pip install requests
Usage
bash

python search_Wikimedia_Commons.py "your search query"

Examples
bash

# Download a cat image
python search_Wikimedia_Commons.py "cat"

# Download a landscape photo
python search_Wikimedia_Commons.py "mountain sunset"

# Download a diagram or illustration
python search_Wikimedia_Commons.py "network topology diagram"
