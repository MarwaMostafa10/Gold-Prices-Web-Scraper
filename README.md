# Gold-Prices-Web-Scraper

📌 Project Description:
This Python script uses Web Scraping techniques to extract real-time gold prices from the iSagha market website (https://market.isagha.com/prices/). The script fetches data on different gold purities, including buy and sell prices, status, and latest price updates, and saves the extracted data into a CSV file for further analysis.

📌 Technologies Used:
Python – Core programming language
Requests – To fetch the webpage content
BeautifulSoup (bs4) – To parse and extract data from HTML
CSV Module – To store the extracted data in a structured format
📌 How It Works:
The script sends an HTTP request to the iSagha gold prices page.
It parses the HTML structure using BeautifulSoup.
Extracts key details for each gold type, including:
Gold Purity (عيار الذهب)
Selling Price (سعر البيع)
Buying Price (سعر الشراء)
Market Status (حالة السوق)
Latest Price Update (آخر تحديث للسعر)
Stores the extracted data in a CSV file (golds_prices.csv) for analysis.
