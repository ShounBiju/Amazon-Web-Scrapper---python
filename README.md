# 🛒 Amazon Web Scraper

## 📌 Project Overview
This project is a **Python-based web scraper** designed to **monitor Amazon product prices** over time. It automatically extracts the **product title, price, and date**, storing the data in a **CSV file** for trend tracking and analysis.  

The scraper can be scheduled to run **daily**, creating a growing dataset to observe price fluctuations, spot discounts, or analyze historical trends. This project demonstrates **web scraping, automation, and basic data pipeline design**.

---

## ⚙️ Tools & Libraries
- **Python 3.x**  
- **BeautifulSoup** – for parsing HTML  
- **Requests** – for sending HTTP requests  
- **Pandas** – for reading and validating CSV data  
- **CSV** – for structured storage of scraped data  
- **Datetime** – for timestamping entries  
- **Time** – for automated scheduling loops  
- **Smtplib** – optional, can be used for notifications

---

## 📦 Dataset
The scraper produces a CSV file named **`AmazonWebScraperDataset.csv`** with the following columns:  

| Column | Description |
|--------|-------------|
| Title  | Product name/title from Amazon |
| Price  | Current product price (numeric) |
| Date   | Date of price retrieval |

**Sample Data:**

| Title | Price | Date |
|-------|-------|------|
| SHSCBSBRK Demon Slayer Tanjiro Anime Soccer Jersey T-Shirt | 84.99 | 2025-09-24 |
| SHSCBSBRK Demon Slayer Tanjiro Anime Soccer Jersey T-Shirt | 84.99 | 2025-09-24 |

---

## 🚀 Features
- **Extract product data** from Amazon product pages (title & price)  
- **Save and append data** to a CSV file for historical tracking  
- **Automated daily checks** using `time.sleep()` to build a growing dataset  
- **Simple data inspection** with Pandas to validate collected records  
- Serves as a **foundation for price monitoring, e-commerce analytics, or alert systems**

---
