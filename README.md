# Tweet Harvest: Tokenizing, Filtering, and Stemming

## Project Description

This project aims to collect, process, and analyze tweet data from Twitter using techniques for tokenization, filtering, and stemming. By utilizing Python and several related libraries, this project allows users to extract information from tweets based on specific keywords.

## Key Features

- **Tweet Data Retrieval**: Uses Tweet Harvest to collect tweets based on keywords.
- **Tokenization**: Breaks down tweet text into individual words for further analysis.
- **Filtering**: Removes irrelevant words (stopwords) and cleans the data.
- **Stemming**: Converts words to their base forms for more efficient analysis.

## Prerequisites

Before running this project, ensure you have:

- Python 3.x
- The following libraries:
  - `pandas`
  - `numpy`
  - `nltk`
  - `Sastrawi`

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/danielmahardhika/tweet-harvest-tokenizing-filtering-stemming.git
   cd tweet-harvest-tokenizing-filtering-stemming
   ```

2. **Install Required Libraries**:
   ```bash
   pip install pandas numpy nltk Sastrawi
   ```

3. **Setup Node.js**: 
   Ensure Node.js is installed on your system to run Tweet Harvest.

## Usage

1. **Run the Notebook**:
   Open the file `tweet-harvest-tokenizing-filtering-stemming.ipynb` in Jupyter Notebook or Google Colab.

2. **Enter Twitter Token**:
   When prompted, enter your Twitter authentication token to access data.

3. **Perform Search**:
   Specify keywords to search for relevant tweets.

4. **View Results**:
   The retrieved data will be saved in CSV format and displayed in the notebook.
