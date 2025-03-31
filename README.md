# IMDb Snow White (2025) Reviews Analysis

## Project Overview

This project analyzes IMDb user reviews for Disney's live-action adaptation of _Snow White (2025)_. Using web scraping and Natural Language Processing (NLP), we assess audience sentiment and identify common themes to provide actionable insights for Disney.

## Problem Statement

Despite the anticipation, early audience reactions on IMDb suggest mixed-to-negative feedback. Our goal is to analyze these reviews to help Disney:

- Understand audience preferences
- Improve marketing strategies
- Enhance future productions

## Key Questions Addressed

1. What is the overall sentiment toward _Snow White (2025)_?
2. What are the most common positive and negative themes?
3. How do audience expectations for live-action remakes compare to animated originals?
4. What aspects of the movie (casting, visuals, storyline) received the most criticism?
5. What recommendations can be made to improve future Disney films?

## Tech Stack

- **Programming Language**: Python
- **Libraries Used**:
  - Web Scraping: Selenium, BeautifulSoup
  - Data Processing: Pandas
  - NLP & Sentiment Analysis: NLTK, VADER
  - Visualization: Matplotlib, Seaborn

## Data Pipeline

### 1. Web Scraping (IMDb Reviews)

- **Tools**: Selenium, ChromeDriver
- **Steps**:
  1. Navigate to IMDb review page
  2. Scroll and load all reviews
  3. Extract review text and ratings
  4. Save data as `imdb_reviews.csv`

### 2. Data Cleaning & Preprocessing

- **Steps**:
  1. Load CSV into Pandas
  2. Tokenize reviews
  3. Remove stopwords & lemmatize tokens
  4. Reconstruct cleaned text

### 3. Sentiment Analysis

- **Tool**: VADER Sentiment Analyzer
- **Steps**:
  1. Compute sentiment scores (Positive, Negative, Neutral, Compound)
  2. Classify sentiment categories
  3. Visualize sentiment distribution

### 4. Insights & Recommendations

- Identify key trends in positive and negative feedback
- Provide data-driven recommendations for Disney

## Deliverables

- **GitHub Repository**: [IMDb-Snow-White-2025-Analysis](#)
- **Dataset**: `imdb_reviews.csv`
- **Report**: Answers to key questions based on analysis
- **Visualizations**: Sentiment distribution graphs

## Contributors

- **Thaddeus Teh**
- **KXLeong**
- **Keshen Naresh**

## How to Run the Project

1. Install dependencies:
   ```sh
   pip install selenium pandas nltk matplotlib seaborn
   ```
2. Run the web scraping script to collect reviews.
3. Execute the sentiment analysis script to process and analyze data.
4. Generate visualizations and insights.

---

This project aims to provide Disney with data-driven recommendations for improving future productions based on audience sentiment analysis.
