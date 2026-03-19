Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

Aim:

Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools.

Explanation:

Develop a python code that integrates multiple AI tool by interacting with their APIs. Compare outputs from different APIs. Analyze the response and the Output.

The aim is to understand how to request help from AI tools for tasks like writing Python code, integrating with APIs, comparing outputs, and generating actionable insights. Code for positive input and output: from nltk.sentiment import SentimentIntensityAnalyzer import nltk

nltk.download('vader_lexicon')

Simulated AI-generated text
generated_text = "This smartphone offers outstanding battery life and an intelligent AI camera that captures stunning photos."

print("Generated Review:\n") print(generated_text)

Sentiment analysis
sia = SentimentIntensityAnalyzer() sentiment = sia.polarity_scores(generated_text)

print("\nSentiment Analysis:") print(sentiment)

Insight generation
if sentiment['compound'] > 0: print("\nInsight: The review is positive and suitable for marketing promotion.") else: print("\nInsight: The review tone is neutral or negative.") Code for negative or neutral input and output: from nltk.sentiment import SentimentIntensityAnalyzer import nltk

nltk.download('vader_lexicon')

Simulated AI-generated text
generated_text = "This smartphone has very bad quality and its perfomance is poor."

print("Generated Review:\n") print(generated_text)

Sentiment analysis
sia = SentimentIntensityAnalyzer() sentiment = sia.polarity_scores(generated_text)

print("\nSentiment Analysis:") print(sentiment)

Insight generation
if sentiment['compound'] > 0: print("\nInsight: The review is positive and suitable for marketing promotion.") else: print("\nInsight: The review tone is neutral or negative.")

Output:
postive output:
<img width="802" height="189" alt="image" src="https://github.com/user-attachments/assets/13602675-15db-4306-bedc-a7a4794ffaa1" />

Negative and Neutral output:
<img width="802" height="187" alt="image" src="https://github.com/user-attachments/assets/dcf7b4d3-1350-48e9-a176-ab293ca732d0" />

Result: 
 Thus Development of Python code compatible with multiple AI Tools has been created and executed successfully
