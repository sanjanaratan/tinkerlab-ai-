# Social Media Sentiment Agent

This mini project explores how to use AI to analyze public sentiment around brands on social media.

I used a few sample tweets about Zomato and ran them through a HuggingFace sentiment analysis model to classify each one as positive, neutral, or negative — along with the model's confidence score.

Even though scraping was down due to certificate issues, I simulated real tweets and completed the full sentiment pipeline. The results were printed and saved to a file.

### What I Used:
- HuggingFace Transformers
- Sentiment Analysis Pipeline
- Python + Pandas
- Tabulate (for a nice display)

This is part of my AI workflow learning series where I try out a new AI build every day — small, useful, and super fun!

Next steps:
- Add LangChain agent logic to auto-analyze tweet sets
- Build a small Streamlit UI

