# Task 3 — News Headlines Web Scraper

## 📌 Project Overview

This project is a simple Python-based web scraper that collects top news headlines from a public news website (e.g., BBC News) and saves them into a text file named `headlines.txt`. 
It demonstrates basic web scraping concepts using **requests** and **BeautifulSoup**.

---

## 📁 Files Included

* **scraper.py** — Main Python script that performs the scraping.
* **headlines.txt** — Output file containing the scraped headlines.
* **README.md** — Documentation for setup and usage.
* **requirements.txt** — Dependencies required to run the script.

---

## ⚙️ Requirements

Install these packages before running the script:

```
requests
beautifulsoup4
```

You can install them using:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run the Scraper

1. Make sure Python 3.7+ is installed.
2. Install dependencies:

   ```bash
   pip install requests beautifulsoup4
   ```
3. Run the script:

   ```bash
   python scraper.py
   ```
4. After running, open `headlines.txt` to see the extracted headlines.

---

## 🔧 Configuration

To change the news source, open **scraper.py** and modify:

```python
URL = "https://www.bbc.com/news"
```

If the site uses different HTML tags for headlines, adjust:

```python
titles = soup.find_all("h2")
```

---

## ⚠️ Notes

* Scraping should comply with the target website's **robots.txt** and Terms of Service.
* Always use a proper `User-Agent` header.
* For large-scale scraping, consider APIs instead.

---

If you want, I can also generate:

* `requirements.txt`
* Code files (`scraper.py`, empty or sample `headlines.txt`)
* A ZIP file containing everything.

Just tell me!
