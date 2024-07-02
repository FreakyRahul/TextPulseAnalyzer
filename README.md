# Text Analysis Project

This project involves scraping content from URLs, performing text analysis, and generating various metrics based on the textual content.

## Project Overview

The project consists of several Python scripts that automate the following tasks:

1. **URL Scraping**: Retrieves content from a list of URLs specified in an Excel file.
2. **Text Analysis**: Analyzes the retrieved content to generate metrics such as sentiment scores, average sentence length, complexity metrics, and more.
3. **Data Processing**: Aggregates the computed metrics into a structured format (Excel) for further analysis or reporting.

## Files Included

- **Main Script**: `main_script.py` - Executes the entire process from URL scraping to metric computation.
- **Input File**: `Input.xlsx` - Contains a list of URLs to scrape.
- **Output File**: `output3.xlsx` - Excel file containing computed metrics for each URL.
- **Stopwords Files**: Several files containing stopwords for filtering text.
- **Word Lists**: `positive-words.txt` and `negative-words.txt` - Lists of positive and negative sentiment words used for sentiment analysis.

## Setup and Dependencies

### Dependencies

The project requires the following Python libraries:

- `pandas`
- `requests`
- `beautifulsoup4`
- `nltk`

You can install these dependencies using pip:

```bash
pip install pandas requests beautifulsoup4 nltk
```

### Execution

To run the script:

1. Ensure all dependencies are installed.
2. Update `Input.xlsx` with the URLs you want to scrape.
3. Execute `main_script.py`.

## Usage Notes

- **Error Handling**: The script includes basic error handling for URL scraping to handle cases where content cannot be retrieved.
- **Customization**: Modify `stop_words` and sentiment word lists (`positive-words.txt`, `negative-words.txt`) as needed for specific applications.
- **Output**: The script generates `output3.xlsx` with computed metrics for each URL scraped.

## Contributors

- **Rahul Sharma**
