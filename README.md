# Flipkart Product Review Scraper

This is a Flask-based web application that scrapes product reviews from **Flipkart** based on a user-provided search term. The app fetches reviews, displays them in a browser, and stores the data in **MongoDB Atlas** for persistence.

## 🚀 Features

- User inputs a product name on the UI
- Scrapes product reviews including:
  - Customer name
  - Rating
  - Review heading
  - Review comment
- Displays scraped reviews on a results page
- Saves reviews to a MongoDB collection
- Supports CORS for cross-origin requests

## 🧰 Tech Stack

- **Python 3**
- **Flask**
- **BeautifulSoup** for HTML parsing
- **requests** and **urllib** for making HTTP calls
- **MongoDB Atlas** via `pymongo`
- **HTML/Jinja2** for templating
- **Flask-CORS** for handling cross-origin requests

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/flipkart-review-scraper.git
   cd flipkart-review-scraper
