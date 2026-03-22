# 🛒 Flipkart Product Data Scraper

A professional **web scraping project** built using Python to extract and analyze product data from Flipkart. This project demonstrates practical skills in data extraction, cleaning, and structuring using a **Jupyter Notebook-based workflow**.

---

## 🚀 Project Overview

This project automates the process of collecting product information from Flipkart, transforming raw HTML into structured datasets suitable for analysis.

It showcases:

* Real-world data extraction
* Data preprocessing techniques
* Working with semi-structured web data

---

## ✨ Key Features

* 🔍 Scrapes multiple product listings
* 📦 Extracts:

  * Product Name
  * Original Price
  * Discounted Price
  * Discount Percentage
  * Customer Ratings
* 🧹 Cleans and structures raw data
* 📊 Converts data into a Pandas DataFrame
* ⚡ Notebook-based execution for easy experimentation

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:**

  * `requests` – HTTP requests
  * `BeautifulSoup` – HTML parsing
  * `pandas` – Data manipulation
* **Environment:** Jupyter Notebook


---

## ⚙️ Installation & Setup

1. Clone the repository:

```bash id="v83ksl"
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Install dependencies:

```bash id="l39skd"
pip install requests beautifulsoup4 pandas notebook
```

---

## ▶️ Running the Project

This project is designed to run in **Jupyter Notebook**:

```bash id="a8dj2k"
jupyter notebook
```

* Open `Flipkart_Project.ipynb`
* Execute cells sequentially
* View extracted and processed data interactively

---

## 🧠 How It Works

1. Sends HTTP requests with headers to simulate a browser
2. Navigates through multiple product listing pages
3. Parses HTML content using BeautifulSoup
4. Extracts relevant product attributes
5. Stores data in structured format (list → DataFrame)

---

## 📊 Sample Output

| Product Name | Original Price | Discounted Price | Discount | Rating |
| ------------ | -------------- | ---------------- | -------- | ------ |
| Example Item | ₹999           | ₹499             | 50%      | 4.3    |

---

## 📈 Skills Demonstrated

* Web Scraping & Data Extraction
* HTML Parsing & DOM Navigation
* Data Cleaning & Transformation
* Python Scripting
* Exploratory Data Handling

---

## ⚠️ Disclaimer

* Intended for **educational purposes only**
* Ensure compliance with website terms of service before scraping
* Avoid excessive requests to prevent server overload

---

## 🔮 Future Enhancements

* Export data to CSV/Excel
* Add logging & exception handling
* Integrate Selenium for dynamic content
* Automate scraping with scheduling tools

---

## 👤 Author

**Malbari Iqra**


---

## ⭐ If you found this useful, consider giving it a star!

---

