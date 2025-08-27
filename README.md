# Google Maps Business Scraper 🗺️

This project is a **Python-based web scraper** that extracts business information from **Google Maps** for a given **industry and city**, then saves the results into an Excel file.

## 🚀 Features
- Scrapes business details from Google Maps:
  - Business Name
  - Rating
  - Phone Number
  - Address
  - Google Maps Link
- Automatically scrolls through results to load more businesses
- Exports clean data to **Excel** (`industry_city.xlsx`)
- Works for any **industry** (e.g., gyms, restaurants, hotels) and any **city/district**

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ykarathnasir/google-maps-business-scraper.git
   cd google-maps-business-scraper
Install dependencies:

bash
Copy code
pip install selenium pandas openpyxl webdriver-manager
Make sure you have Google Chrome installed.

⚙️ Usage
Open the script file maps_business_scraper.py

Update the CONFIG section:

python
Copy code
CONFIG = {
    "district": "Colombo",
    "city": "Maharagama",
    "country": "Sri Lanka",
    "industry": "gyms",
    "max_results": 20
}
Run the script:

bash
Copy code
python maps_business_scraper.py
The output Excel file will be saved as:

Copy code
gyms_Maharagama.xlsx
📂 Output Example
Name	Phone	Rating	Address	Google_Maps_Link
Fit Life Gym	+94 77 1234	4.5	123 Main St, Maharagama, Colombo	maps.google.com/...
Power House Fitness	+94 71 5678	4.2	45 High Level Rd, Maharagama	maps.google.com/...

⚠️ Disclaimer
This tool is for educational and research purposes only.

Scraping Google Maps may violate Google’s Terms of Service. Use responsibly.

The author is not responsible for misuse.

📝 License
MIT License
