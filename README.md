# Financial Services Tracker

Technologies: Python, NLTK, PRAW, Streamlit, BeautifulSoup, Selenium, Pandas

### Overview

The Financial Services Tracker is a live dashboard that scrapes and analyzes public data from Canadian fintech competitors such as Questrade and IBKR. It tracks app reviews, pricing updates, and product announcements, and uses rule-based sentiment analysis (NLTK) to extract insights about customer perception and market trends.

Features
- Automated Data Collection: Scrapes app store reviews, Reddit discussions (via PRAW), and official pricing pages.
- Sentiment Analysis: Uses NLTK to classify feedback as positive, negative, or neutral with simple rule-based heuristics.
- Real-Time Insights: Displays aggregated sentiment scores, trending topics, and competitor updates.
- Interactive Dashboard: Streamlit interface for live filtering by platform, time range, or keyword.


Example Outputs
- Sentiment trends for app reviews over time
- Word clouds of common complaints or praise
- Comparative pricing charts across competitors

Next Steps
- Integrate machine learning-based sentiment models (e.g., BERT)
- Add database storage for historical tracking
- Expand coverage to U.S. fintech competitors
