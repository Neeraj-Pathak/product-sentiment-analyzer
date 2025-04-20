Product Sentiment Analyzer using LangChain
This repository contains a Python implementation of a Product Sentiment Analyzer leveraging the LangChain library to analyze customer feedback. The tool uses natural language processing (NLP) models to detect negative sentiment across different product categories and store locations based on customer reviews.

Features:
Sentiment Detection: Analyzes customer feedback to classify sentiment as negative or positive.
Category Association: Associates negative feedback with the appropriate product category (e.g., clothing, electronics, etc.).
Store Location Insights: Identifies the store location with the highest number of customer complaints.
Custom LangChain Chain: Uses LangChain to process the data and extract meaningful insights from customer feedback.
Simple API Integration: Integrates with external APIs for enhancing sentiment analysis and retrieving real-time information when needed.

Technologies Used:
LangChain: To facilitate chain-based processing and sentiment analysis using LLMs.
NLP Models: Pre-trained language models for sentiment analysis and category classification.
Python: The primary language for scripting and data processing.

Requirements:
langchain
requests
langchain_nvidia_ai_endpoints

Installation:

Clone the repository:
bash
git clone <repository_url>

Install the required dependencies:
bash
pip install -r requirements.txt

Usage:
You can run the script directly to analyze customer emails and identify the product category with the most negative sentiment and the store location with the highest number of complaints.
bash
python sentiment_analyzer.py
