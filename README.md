# CODEXINTERN PROJECT - Python Development Intern

# Task1 : Sentiment_Analysis

# Title:  Text-Based Emotion Detection using Flask and TextBlob

This project involves developing a sentiment analysis tool using Flask, a popular Python web framework, and TextBlob, a Python library for sentiment analysis. The tool takes a text input from the user and analyzes it to determine the emotional tone or sentiment behind the text. The tool will then output the sentiment as positive, negative, or neutral.

**Features**
- Accurate Sentiment Analysis: The tool uses TextBlob to accurately detect the sentiment of the text input.
- Easy-to-Use Interface: The tool has a simple and intuitive interface that makes it easy for users to enter text and get sentiment analysis results.
- Fast Processing: The tool processes text inputs quickly and efficiently, providing users with fast and accurate sentiment analysis results.

**How it Works**
1. Text Input: The user enters a text input into the tool.
2. Sentiment Analysis: The tool analyzes the text input using TextBlob to determine the sentiment.
3. Sentiment Output: The tool outputs the sentiment as positive, negative, or neutral.

**Technologies Used**
- Flask: The tool is built using Flask, a popular Python web framework.
- TextBlob: The tool utilizes TextBlob, a Python library for sentiment analysis.
- Python: The tool is built using Python, a popular programming language.

**How to Use**
1. Enter Text: Enter a text input into the tool.
2. Get Sentiment Analysis Results: The tool will analyze the text input and output the sentiment as positive, negative, or neutral.

**Learning Outcomes**
- Understanding of Sentiment Analysis: Gain a comprehensive understanding of sentiment analysis and its applications.
- Knowledge of TextBlob: Learn how to use TextBlob for sentiment analysis.
- Experience with Flask: Develop skills in using Flask for building web applications.


# Task 2 : Google Search Scraper

# Title: Automated Google Search Results Scraper using Python and BeautifulSoup

This project involves developing a tool that performs Google searches and extracts the top results, including titles, links, and short descriptions. It uses Python libraries like requests and BeautifulSoup to fetch and parse HTML data. This tool can be helpful for quick research, content ideas, or SEO analysis.

**Features**
- Automated Google Searches: Automatically performs Google searches based on user input.
- Top Results Extraction: Extracts result titles, URLs, and short descriptions from search results.
- Simple & Fast: Lightweight script that runs from the command line.
- Customizable: Easy to modify for advanced scraping needs (e.g., filters, output formats).

**How It Works**
1. User Input: The user provides a search query.
2. Google Search Request: The script sends a request to Google (through a workaround like startpage.com or serpapi since direct scraping is blocked).
3.  HTML Parsing: Parses the returned HTML using BeautifulSoup.
4.   Result Extraction: Gathers and displays the title, link, and description of each result.

💻 **Technologies Used**

- Python: Programming language used to write the script.
- Requests: To send HTTP requests to the search engine.
- BeautifulSoup: To parse and extract data from the HTML response.
- lxml (optional): Faster parser for BeautifulSoup.

🚀**How to Use**
1. Install Required Libraries:
bash
Copy
Edit
pip install requests beautifulsoup4 lxml

2. Run the Script:
bash
Copy
Edit
python scraper.py "your search query"

3. View Results:
The script will output the search results including titles, links, and short snippets.

📚 **Learning Outcomes**
- Web Scraping Basics: Learn how to extract content from web pages.
- HTML Parsing: Understand how to use BeautifulSoup to navigate and search through HTML data.
- HTTP Requests in Python: Learn how to make and handle HTTP requests using requests.


🔐 Note on Google Scraping
Direct scraping of Google results often results in CAPTCHAs or blocks. Consider using search APIs like:

SerpAPI

Google Custom Search API

Or use privacy search engines like StartPage that proxy Google results legally















