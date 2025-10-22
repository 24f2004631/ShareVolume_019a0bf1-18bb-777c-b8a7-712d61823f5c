# ShareVolume App

This application fetches and displays the maximum and minimum common stock shares outstanding for a given company, based on data from the SEC EDGAR API.

## Features

- Displays company name, maximum shares outstanding, and minimum shares outstanding with their respective fiscal years.
- Supports dynamic loading of data for different CIKs via URL query parameters (`?CIK=`).

## How to Run

1. Open `index.html` in your web browser.
2. To view data for a different company, append `?CIK=YOUR_CIK_NUMBER` to the URL.
   Example: `index.html?CIK=0001018724`

## Data Source

Data is sourced from the SEC EDGAR API: `https://data.sec.gov/api/xbrl/companyconcept/CIK<CIK_NUMBER>/dei/EntityCommonStockSharesOutstanding.json`

## License

This project is licensed under the MIT License.
