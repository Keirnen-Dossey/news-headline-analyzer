# News Headline Analyzer

This project showcases end-to-end data handling skills using real-time news headlines. It scrapes articles from NPR and BBC, categorizes them based on topic (e.g., politics, technology, world), and generates concise keyword-based summaries using natural language processing techniques. The final output is structured and exported to a CSV file for further analysis or visualization.

The goal of this project was to simulate a real-world data task involving the collection, cleaning, transformation, and presentation of unstructured text data. It was developed to strengthen my portfolio for data analyst roles.

---

## Features

- Scrapes live headlines from NPR and BBC
- Categorizes news stories using custom keyword matching
- Summarizes content using keyword extraction (RAKE algorithm)
- Outputs results into a structured CSV for external use (e.g., Tableau, Excel)

---

## Tools and Libraries

- Python 3
- pandas
- BeautifulSoup
- feedparser
- rake-nltk
- TextBlob
- nltk

---

## How to Run

1. Clone the repository or download the notebook
2. Install required libraries:
   ```bash
   pip install pandas beautifulsoup4 feedparser rake-nltk textblob
   python -m textblob.download_corpora
   python -c "import nltk; nltk.download('stopwords')"
