# 🇦🇹 Vienna District Crime Map 2024
An interactive, multilingual Choropleth map visualizing reported crime statistics across Vienna's 23 districts.

[Live Demo Link](https://fnburger.github.io/viennaCrimeMap/)

## Features
* **Interactive Choropleth Map:** Color-coded districts based on crime density using Leaflet.js. Switch between absolute values and relative (per 1k citizens).
* **Multilingual Support:** Dynamic language switching between **English**, **German**, and **Chinese (Simplified)**.
* **Detailed Tooltips:** Clickable districts showing formatted names and exact case numbers.
* **Data Accuracy:** Visualizes 2024 official statistics with a high-contrast red-to-yellow safety scale.

## Tech Stack
* **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
* **Mapping:** [Leaflet.js](https://leafletjs.com/)
* **Data Format:** GeoJSON (filtered for Vienna)
* **Backend (Automation):** Python 3 (Used for data preprocessing and future scraping)

## Data Source
Crime statistics are derived from the **Austrian Federal Criminal Police Office (Bundeskriminalamt)** PKS 2024 report.
> [Source PDF](https://www.bundeskriminalamt.at/501/files/PKS-24-web3_bf_20250919.pdf)

## Project Structure
* `index.html`: The main web application.
* `vienna_bezirke.geojson`: Optimized geographic boundaries for Vienna's 23 districts.

## Future Roadmap
- [ ] **Real-time Updates:** Implement a scraper to fetch detailed monthly crime reports from the *Polizei Wien* press portal and visualize them in a more fine-grained map.
