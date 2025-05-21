# 📱 Smartphone Data Scraper

This repository provides a basic implementation of web scraping smartphone data from a **dynamic website** using **Selenium** and **BeautifulSoup** in Python.

## 🚀 Overview

Dynamic websites load content through JavaScript, making it difficult for traditional scraping libraries like `requests` to capture the complete data. To overcome this, we use:

- **Selenium** to render and interact with dynamic content as a real browser would.
- **BeautifulSoup** to parse and extract meaningful smartphone data from the rendered HTML.

## 🔍 What It Does

The scraper extracts the following information about smartphones:

- 📛 Brand & Model Name  
- ⚙️ Specifications (RAM, Storage, Processor, Battery, Camera, etc.)  
- 💵 Price  
- ⭐ Ratings or Reviews (if available)

## 🧰 Technologies Used

- Python 3
- Selenium
- BeautifulSoup (bs4)
- WebDriver (e.g., ChromeDriver)

## 📝 How It Works

1. Selenium opens the target website in a browser window.
2. It waits for all JavaScript content (e.g., product cards) to load.
3. Once fully loaded, the HTML source is passed to BeautifulSoup.
4. BeautifulSoup extracts the desired smartphone details.
5. The data is cleaned and exported to a CSV or JSON file.


