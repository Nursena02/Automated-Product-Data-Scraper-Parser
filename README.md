# Automated Product Data Scraper & Parser 🕷️📊

This repository features a robust **Python**-based data acquisition tool developed to automate the extraction, cleaning, and structuring of product information from e-commerce web platforms. 

## 🎯 Project Overview
The project demonstrates a complete data pipeline: from handling HTTP protocols to navigate web structures, to parsing unstructured HTML and exporting "analysis-ready" datasets in CSV format.

## 🛠 Technical Implementation
* **Web Scraping:** Leveraged the `Requests` library to manage HTTP communications and retrieve raw HTML content from target URLs.
* **HTML Parsing:** Employed `BeautifulSoup4` with precise CSS selectors to traverse complex DOM trees and isolate key product attributes such as names, prices, and categories.
* **Data Normalization:** Engineered a custom cleaning logic to strip unwanted characters (currency symbols, whitespace) and handle missing values, ensuring high data integrity.
* **Structured Export:** Automated the serialization of processed data into **CSV** files, optimized for immediate use in data science and machine learning workflows.

## 💻 Tech Stack
* **Language:** Python 3.x
* **Libraries:** BeautifulSoup4, Requests, CSV, Urllib
* **Concepts:** DOM Traversal, Data Cleaning, ETL (Extract, Transform, Load)

## 🚀 How to Use
1. **Clone the repo:** `git clone https://github.com/Nursena02/Product-Data-Scraper-Parser.git`
2. **Install dependencies:** `pip install beautifulsoup4 requests`
3. **Run the script:** Execute the main Python file to start the automated scraping and see the generated `output.csv`.

---
*This project was developed as a technical assessment for DFA Teknoloji, showcasing the ability to build efficient tools for large-scale web data extraction.*
