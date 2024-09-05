# Text Summarization and Web Scraping

This project demonstrates how to use web scraping techniques with BeautifulSoup to extract text data from a Wikipedia page and perform text summarization using both word frequencies and N-grams.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [License](#license)
- [Notes](#notes)

## Overview

1. **Web Scraping with BeautifulSoup**
   - Extract text data from the specified Wikipedia page.
   - Preprocess the text by tokenizing, removing stop words, and punctuation.

2. **Text Summarization**
   - **Word Frequency Summarization**: Calculate word frequencies, score sentences, and generate summaries based on sentence count, word count, and percentage.
   - **N-gram Summarization**: Generate N-grams, calculate their frequencies, and summarize text based on N-gram frequencies.

## Installation

Make sure you have Python installed on your machine. You can install the necessary libraries using pip:

```bash
pip install beautifulsoup4 requests nltk
```
## Usage

To use this project, follow these steps:

1. **Run Web Scraping:**
   - Execute the provided Python script to scrape text data from the Wikipedia page. The script uses BeautifulSoup to extract the content from the specified URL.

2. **Perform Text Summarization:**
   - After scraping the text, run the summarization script to apply both word frequency and N-gram techniques.
   - You can specify different summarization parameters such as sentence count, word count, and percentage to generate summaries.

In the script, you will find functions to:

Fetch and parse HTML content from the Wikipedia page.
Tokenize and preprocess the text.
Calculate word frequencies and N-grams.
Score sentences and generate summaries based on various criteria.

## Data

The data for this project is sourced from the Wikipedia page on Natural Language Processing:

**URL**: https://en.wikipedia.org/wiki/Natural_language_processing
The project extracts text from the main content section of the Wikipedia page. No additional data is required for running the project beyond this URL.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
