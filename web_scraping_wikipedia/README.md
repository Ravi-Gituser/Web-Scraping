# web_scraping
This is the code for the "Build a Web Scraper".

#Overview
This is the code to build a web scraper. This script pulls the top 20 most frequently used words from a Wikipedia article. It uses regular expressions and stop word removal to create a cleaned table that we can view with the results.

#Installation

The necessary dependencies are in the requirements.txt file so just run this before running the actual code to get them installed.

``
pip install -r requirements.txt
``

#Usage

There are two arguments. The first is the article you want to retrive words from. The second is a boolean value that describes
whether or not you want to remove stop words. 

``
python main.py your_article_name_here yes
``


