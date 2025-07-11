# Social Media Sentiment Agent

This project is a simple, smart, and completely free AI workflow that analyzes public sentiment from social media posts — no OpenAI, no cost.

I used HuggingFace's transformer models (like BERT) to classify tweets about brands like Zomato into positive, negative, or neutral tones, along with confidence scores.

It was part of my AI exploration series where I’m learning how to build intelligent tools using minimal code but maximum creativity.

###  Why I Skipped OpenAI
Most projects use OpenAI to make tools chatty or interactive — but I wanted to show that you don’t *need* GPT for everything.

This sentiment tool uses:
-  HuggingFace’s BERT sentiment model (`nlptown/bert-base-multilingual-uncased-sentiment`)
-  A simple Python wrapper to simulate an assistant
-  No API keys, no rate limits, no cost

### How It Works
1. The script takes a tweet (or multiple)
2. Runs it through a HuggingFace model
3. Returns a sentiment label (like 1 star to 5 stars) with confidence
4. (Optional) Saves results to a CSV


