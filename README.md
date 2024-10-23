This project is a simple web scraping tool designed to extract book titles from the website "Books to Scrape."

### Prerequisites
- Python 3.x
- Libraries:
  - `requests`: To send HTTP requests and get the webpage.
  - `BeautifulSoup` (from `bs4`): For parsing the HTML content.

### How It Works
1. The script sends a GET request to the website's homepage.
2. It parses the HTML response to locate all book titles within `<h3>` tags.
3. The script extracts and prints the titles.

### How to Run
1. Install required libraries: `pip install requests beautifulsoup4`
2. Run the script in your Python environment.
