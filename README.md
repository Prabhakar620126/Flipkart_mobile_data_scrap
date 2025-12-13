# 📱 Flipkart Mobile Phones Web Scraper 

A Python-based web scraping project that extracts real customer-facing data of mobile phones from Flipkart, categorized company-wise, using requests, BeautifulSoup, and time libraries.



## 📌 1. Project Overview
  - The purpose of this project is to:
  - Scrape mobile phone data from Flipkart
  - Collect info for Top 10 Mobile Companies
  - Extract name, price, ratings, reviews, specifications, storage, RAM, etc.
  - Store the extracted data in a structured format (CSV/Excel)


## 🎯 2. Problem Statement
  - Flipkart displays hundreds of mobile phone listings across each brands.
  - Does not allow downloading product information directly
  - Shows dynamic content
  - Displays data across multiple pagination pages

This scraper solves the problem by:
  ✔ Automating page navigation
  ✔ Extracting structured data for each mobile brand
  ✔ Organizing results company-wise
  ✔ Creating a dataset suitable for analysis

 ## 📂 3. Raw Data (Scraping Result)
📥 Download Final Scraping Output (CSV)

[all_mobile_data.xlsx](https://github.com/Prabhakar620126/Flipkart_mobile_data_scrap/blob/main/Mobile_phone_data_from_Flipkart.xlsx )

## 🖼 4. Screenshots (Before & After Scraping)

🔍 Before Scraping – <a href="https://github.com/Prabhakar620126/Flipkart_mobile_data_scrap/blob/main/flipkart.png">Flipkart Website View</a>

📊 After Scraping – <a href="https://github.com/Prabhakar620126/Flipkart_mobile_data_scrap/blob/main/mobile_data.png">Terminal Output</a>

## 🛠 5. Python Code File
🐍 View Python Script

[scraper.py](https://github.com/Prabhakar620126/Flipkart_mobile_data_scrap/blob/main/Mobile_data_from_multiple_page.ipynb )


## 🏢 6. Top 10 Companies Scraped
This project scrapes data for the following brands:
| Rank | Brand             |
| ---- | ----------------- |
| 1    | Apple             |
| 2    | Motorola          |
| 3    | Redmi             |
| 4    | Vivo              |
| 5    | Oppo              |
| 6    | Realme            |
| 7    | Samsung           |
| 8    | POCO              |
| 9    | Google Pixel      |
| 10   | Infinix           |

## 🛠 7. Libraries & Technologies Used
  requests       → To send HTTP GET requests  
  BeautifulSoup  → To parse HTML and extract data  
  time           → To add delays between requests  
  CSV / Pandas   → To store scraped data  

## ⚙️ 8. How It Works (Scraping Workflow)
1️⃣ Send request to Flipkart search URL for each company
2️⃣ Parse HTML using BeautifulSoup
3️⃣ Extract:
  - Mobile name
  - Price
  - MRP
  - Ratings
  - Number of reviews
  - RAM / Storage
  - Processor
  - Battery capacity
  - Camera specifications
4️⃣ Navigate Pagination
5️⃣ Store company-wise data into separate CSV files
6️⃣ Combine all data into a master dataset

## 🧾 9. Output Format (Final CSV Columns)
  - brand
  - product_name
  - price
  - mrp
  - rating
  -reviews_count
  - ram
  -storage
  - processor
  -camera
  -battery
  -product_link

## ✔ 10. Features of This Project
| Feature                           | Description                                  |
| --------------------------------- | -------------------------------------------- |
| 🔍 **Company-wise scraping**      | Scrapes top 10 brands separately             |
| 📄 **Pagination handling**        | Collects data from all pages                 |
| 📱 **Real customer visible data** | Only extracts what customers see on Flipkart |
| ⏳ **Human-like scraping**         | Uses `time.sleep()` to avoid getting blocked |
| 🎯 **Clean structured data**      | CSV output for analysis or ML                |
| 🔧 **Fully customizable**         | Add/remove brands or fields easily           |

  ## 📌 11. Ethical Disclaimer 
Flipkart website content belongs to Flipkart Pvt. Ltd.
This project is for educational and research purposes only.
✔ We follow ethical scraping guidelines:
  - Add time.sleep() delays
  - Do not overload servers
  - Scrape only publicly visible information
  - No login, no bypassing security
❌ Do not use scraped data for commercial resale.

## 📥 12. Future Enhancements 
  - Add AI-based sentiment analysis of reviews
  - Add price prediction model
  - Add SQLite database storage
  - Include image URLs
  - Build a Power BI dashboard for visualization

# 🙌 Author  
**PRABHAKAR KUMAR SHAHI**  
📧 Email: prabhakar620126@gmail.com 
🔗 GitHub: https://github.com/Prabhakar620126
