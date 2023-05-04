# Web Scraping GitHub Trending Topics
This project is a Python script that uses the Requests and Beautiful Soup libraries to scrape the trending topics on GitHub. The script collects the title, description, author, and number of stars for each repository listed in the trending topics section.

## Requirements
To run this project, you'll need:
* Python 3.x
* Requests library (pip install requests)
* Beautiful Soup library (pip install beautifulsoup4)
* Jupyter Notebook (pip install notebook)

## Usage
1.Clone this repository or download the script file (Github-Topic.ipynb)

2.Open a terminal and navigate to the directory where the script is located.

3.Run the script using the command python Github-topic.ipynb in jupyter notebook

4.The script will scrape the GitHub trending topics and creates a CSV file of collected data.


### CSV File
* Topic -> Topic name in first column
* Description -> Description of topic 
* Url -> Link of topic page

### Limitations
Please note that this script in only for learning purpose and also web scraping can be a legally gray area and may violate a website's terms of service. 
In addition, scraping too much data too quickly can put a strain on the website's servers and impact their performance. Use this script responsibly and with caution.
