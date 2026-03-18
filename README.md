# World Explorer 🌍

An interactive, lightweight, and fully client-side web application that lets users explore the globe. Click on any country to instantly view its flag, core statistics, and detailed overviews fetched dynamically from public APIs. 

## ✨ Features

* **Interactive D3.js Map:** Smooth panning, zooming, and hover states across a beautifully rendered globe.
* **180+ Clickable Territories:** Identifies and maps standard ISO numeric codes to country names.
* **Zero-Backend Architecture:** 100% serverless. All data is fetched directly from the client.
* **Live API Integrations:** * Automatically fetches high-quality SVG flags, population, area, and capital city data via the **REST Countries API**.
  * Pulls live historical and cultural overviews using the **Wikipedia REST API**.
* **Smart Search:** Built-in search bar with autocomplete to quickly find and jump to specific countries.
* **Modern UI/UX:** Features glassmorphism panels, skeleton loading animations for images, and responsive design elements.

## 🛠️ Technologies Used

* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Data Visualization:** D3.js (v7), TopoJSON
* **Map Data:** World Atlas (110m resolution)
* **APIs:** * [REST Countries API](https://restcountries.com/)
  * [Wikipedia REST API](https://en.wikipedia.org/api/rest_v1/)

## 🚀 Getting Started

Because this project is entirely frontend-based, there is no build step or node package installation required.

### Local Development
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/world-explorer.git](https://github.com/yourusername/world-explorer.git)
