# Wikipedia Scraper
This project is a simple web scraper that retrieves the text content from a Wikipedia page for a given topic. The scraper uses `requests` to fetch web pages and `BeautifulSoup` to parse the HTML content. The extracted text is cleaned of citation references and saved to a text file.

## Features

- Takes a user input topic and searches for its Wikipedia page via Google search.
- Extracts the text content from the Wikipedia page.
- Cleans the text by removing citation references.
- Saves the cleaned text to a file.

## Requirements

- Python 3.x
- `requests` library
- `BeautifulSoup` library

## Installation

1. Clone the repository or download the script file.
2. Install the required libraries if you haven't already:

   ```bash
   pip install requests
   pip install beautifulsoup4
