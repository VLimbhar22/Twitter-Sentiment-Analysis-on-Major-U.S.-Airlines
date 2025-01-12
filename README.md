# Twitter Sentiment Analysis on Major U.S. Airlines

This project analyzes public sentiment toward major U.S. airlines based on tweets. By leveraging Natural Language Processing (NLP) techniques, the project identifies whether tweets are positive, neutral, or negative, providing insights into customer opinions and trends.

---

## Objectives
- Scrape and analyze tweets mentioning major U.S. airlines.
- Perform sentiment classification on the tweets.
- Visualize sentiment distribution and trends for actionable insights.

---

## Dataset
- **Source**: Publicly available tweets about major U.S. airlines.
- The dataset includes:
  - Tweet content
  - Timestamp
  - Sentiment labels (Positive, Neutral, Negative)

---

## Technologies and Tools
This project uses the following technologies:
- **Data Collection**: `Tweepy` (Twitter API)
- **Data Cleaning**: `pandas`, `numpy`
- **Sentiment Analysis**: `TextBlob`, `NLTK`
- **Visualization**: `matplotlib`, `seaborn`, `wordcloud`

---

## Key Steps
1. **Data Collection**:
   - Scraped tweets using `Tweepy` and the Twitter API, filtering mentions of major U.S. airlines.
   - Collected relevant metadata like tweet text and timestamps.

2. **Data Cleaning**:
   - Removed special characters, URLs, and stopwords from the tweets.
   - Tokenized text for further analysis.

3. **Sentiment Analysis**:
   - Used `TextBlob` to classify tweets into positive, neutral, or negative sentiment.
   - Calculated polarity scores to quantify the sentiment intensity.

4. **Visualization**:
   - Created bar charts to display sentiment distribution across airlines.
   - Generated word clouds to highlight commonly mentioned terms.
   - Plotted sentiment trends over time.

---

## Results
- **Sentiment Breakdown**:
  - Identified which airlines had the highest positive and negative sentiment.
- **Trending Issues**:
  - Negative sentiment often correlated with delays, cancellations, and poor customer service.
- **Visualization Highlights**:
  - Word clouds showcasing frequent terms in positive and negative tweets.
  - Trend analysis revealing sentiment patterns over time.

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/VLimbhar22/Twitter-Sentiment-Analysis-on-Major-U.S.-Airlines
   cd Twitter-Sentiment-Analysis-on-Major-U.S.-Airlines
