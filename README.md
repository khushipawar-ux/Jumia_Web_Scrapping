# Jumia_Web_Scrapping
Scrapping of a E-Commerce Website called Jumia

## 📌 Overview

This project is a web scraper for **Jumia**, an e-commerce platform. It extracts product details such as names, prices, ratings, and product links, providing structured data for analysis or automation.

## 🔥 Features

- Scrapes product names, prices, ratings, and URLs
- Supports pagination for retrieving multiple pages
- Saves data in CSV/JSON formats
- Built using **Python** with **BeautifulSoup** and **Requests**
- Simple and easy-to-use CLI interface

## 🛠️ Installation

### Prerequisites
Ensure you have **Python 3.x** installed on your system.

### Clone the Repository
git clone https://github.com/your-username/jumia-scraper.git
cd jumia-scraper

### Install Dependencies
pip install -r requirements.txt

## 🚀 Usage
Run the script with:
python scraper.py --category "laptops" --pages 3


### Arguments:
- `--category`: The product category to scrape (e.g., "laptops", "phones").
- `--pages`: Number of pages to scrape (default: 1).

### Example Output
Scraping Jumia for category: Laptops
Page 1: 20 products scraped
Page 2: 20 products scraped
Saved data to jumia_laptops.csv

Let me know if you need modifications! 🚀
