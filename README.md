# web-scraping
Web scraping Yahoo! Finance using requests and Beautiful Soup.

Built functions such as download_web_page() to download any url and create a document to be parsed, parse_volume_tag() to strip and convert any number followed by a k, M, or B into an integer, parse_stocks() to parse through a beautifulSoup doc and create a dictionary of information, list_tickers() to create a list of stock tickers from a dictionary, and write_csv() to save any beautifulSoup document as a csv file.

Stored data consisting of 100 rows x 9 columns and 30 rows x 7 columns into a csv file using Pandas.

Check out the Jupyter notebook | https://jovian.ai/nadya-debeers/web-scraping-with-python-project
