# sentiment_analysis_charlie_kirk-


# Charlie Kirk Twitter Sentiment Analysis

## Overview
Analysis of Twitter discourse surrounding Charlie Kirk over a 36-hour period using NLP and sentiment analysis.

## Dataset Coverage
- **Search Query**: Tweets containing `#CharlieKirk` OR `"Charlie Kirk"`
- **Time Period**: Last 36 hours
- **Privacy**: All usernames and IDs obfuscated with unique hashids
- **Well-Known Authors**: Blue-verified (10K+ followers) or non-verified (50K+ followers)

## Methodology
1. **Data Preprocessing**: Text cleaning, tokenization, stopword removal
2. **Sentiment Analysis**: NLTK sentiment polarity scoring
3. **Topic Extraction**: Key themes and topic modeling
4. **Visualizations**: Word clouds, sentiment distribution, topic graphs

## Key Findings
- [Overall sentiment breakdown]
- [Most discussed topics]
- [Temporal patterns]

## How to Run
```bash
# Clone repository
git clone https://github.com/yourusername/charlie-kirk-sentiment.git

# Install dependencies
pip install -r requirements.txt

# Run analysis
python main.py
```

## Technologies Used
- Python 3.9+
- NLTK
- Pandas, NumPy
- Matplotlib, Seaborn
- WordCloud
