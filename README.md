🛍️ Amazon Product Scraper (Python + Selenium)
📖 Overview
This project is a web scraping tool that automatically extracts product details from Amazon India pages.
It uses Selenium to simulate a real browser, navigate product pages, and collect structured data such as:
Product Title
Price
Rating
Review Count
Availability
The scraped data is saved into a CSV file for analysis or further processing.

⚙️ Features

✅ Works with multiple product URLs (from a text file)
✅ Automatically scrolls pages to load dynamic content
✅ Handles missing data gracefully (NA values)
✅ Headless mode supported (optional background scraping)
✅ User-agent spoofing for better request reliability

🧩 Technologies Used

Python 3.x
Selenium WebDriver
Google Chrome / ChromeDriver
CSV for structured output

📁 Project Structure
amazon_scraper/
│
├── scrapper_code.ipynb        # Main scraping script
├── url.txt                  # Input file with product URLs (one per line)
├── scrapped.csv       # Output file (generated automatically)
└── README.md                # Project documentation

🚀 Setup & Installation
1️⃣ Install Dependencies
Make sure Python is installed, then install Selenium:
pip install selenium
2️⃣ Download ChromeDriver
Go to ChromeDriver Downloads
Match it with your Chrome version
Place chromedriver.exe in the same folder as your script (or add it to PATH)

📜 How to Use
Step 1: Add URLs
Create a text file named url.txt and paste your Amazon product links (one per line).
Example:
https://www.amazon.in/dp/B0CZXZG1BW
https://www.amazon.in/dp/B0BQL21KRP
Step 2: Run the Script
Run the file:
scrapper_code.ipynb
Step 3: View Results
After the run completes, you’ll see:
scrapped.csv

Example output:

Title	Price	Rating	Review Count	Availability
ZAVERI PEARLS Green Meenakari Kundan Necklace	835	4.1 out of 5 stars	299 ratings	In stock

🧠 Future Improvements

Add proxy rotation to avoid detection
Support scraping multiple Amazon domains (.com, .uk, .ca)
Export to Excel or database (MySQL)
Integrate with Power BI for visualization

👩‍💻 Author

Shalini Ponia
💡 Engineering student passionate about Data Analytics 
📧 Contact: [shaliniponia146@gmail.com]
