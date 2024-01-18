# text-analysis
webtext analysis with ntlk
Webpage Text Analytics with NLTK
Overview
This Python script performs basic text analytics on a webpage using NLTK (Natural Language Toolkit). It follows the steps outlined below:

Downloads a webpage using the provided URL using the requests and BeautifulSoup libraries.
Splits the text into sentences, tokenizes it, performs POS tagging, removes stop words, and applies lemmatization using NLTK.
Plots a frequency distribution of the most important words in the document before and after lemmatization.
Provides information on the top 5 and bottom 5 words before and after lemmatization.
Dependencies
Python 3.x
Install required packages using the following:
bash
Copy code
pip install requests beautifulsoup4 nltk matplotlib
Usage
Open the Python script (webpage_text_analytics.py) in your preferred editor.
Replace the webpage_url variable with the URL of the webpage you want to analyze.
Run the script.
Output
The script will generate two plots showing the frequency distribution of words before and after lemmatization. Additionally, it will print the top 5 and bottom 5 words before and after lemmatization.
