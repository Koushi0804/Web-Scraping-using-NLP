# Web-Scraping-using-NLP
# Text Analysis Tool

This project is a text analysis tool that extracts data from URLs, performs various textual analyses, and saves the results in an Excel file.

## Features

- Extracts article text from URLs using web scraping techniques
- Performs sentiment analysis using NLTK's SentimentIntensityAnalyzer
- Computes various text metrics including sentence length, complexity, word count, etc.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/text-analysis-tool.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Add stop words to the `/StopWords` directory.
2. Add positive and negative word lists to the project root.
3. Prepare an input Excel file (`Input.xlsx`) with URL_ID and URL columns.
4. Run the main script `text_analysis.py` to perform text analysis.
5. Check the generated `MyCombined_Output.xlsx` for the results.

## Project Structure

- `text_analysis.py`: Main script for performing text analysis.
- `/StopWords`: Folder containing stop words for text cleaning.
- `positive-words.txt`: List of positive words.
- `negative-words.txt`: List of negative words.
- `Input.xlsx`: Input file containing URLs for analysis.


