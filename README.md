# The Arabic Clock | Mecca Timekeeping (Ghurubiyah)

A sophisticated web-based timepiece inspired by traditional **Mecca Timekeeping** and **Andalusian design**. This project visualizes **Arabic Time (Ghurubiyah)**, a historical system where the day begins precisely at sunset, aligning human activity with the natural solar cycle.

<img width="618" height="712" alt="image" src="https://github.com/user-attachments/assets/9de15788-2c00-42ca-94ef-38534e487730" />

## 🌟 Key Features

### 🕰️ The Dual-Dial System
* **Main Dial (Arabic Time):** The primary hands track the time elapsed since the last sunset. In this system, **12:00 is always Sunset (Maghrib)**.
* **Sub-Dial (Standard Time):** A sophisticated complication at the bottom displays your local civil time (Standard/Phone time) for modern coordination.

### ☀️ Solar Tracking
* **Golden Sun Pointer:** A dedicated arm tracks the actual physical position of the sun in the sky (Rising vs. Setting) and displays the percentage of daylight remaining.
* **Dynamic Markers:** Two static arms on the face indicate the exact solar time of **Sunrise** and **Sunset** for the current day, adjusting automatically based on the season.

### 📍 Geolocation & Astronomy
* Automatically detects the user's location to fetch accurate astronomical data.
* Powered by the [Sunrise-Sunset API](https://sunrise-sunset.org/api).
* **Bilingual:** Includes both English (`index.html`) and Arabic (`ar.html`) versions with fully localized layouts (RTL) and Eastern Arabic numerals (١, ٢, ٣).

## 🎨 Design & Aesthetics
* **Andalusian Influence:** Features a procedural SVG geometric rosette background typical of Islamic art.
* **Typography:** Uses *Cinzel* for the English antique look and *Amiri* (Naskh style) + *Cairo* for the Arabic version.
* **Responsiveness:** Built with Tailwind CSS to look beautiful on mobile and desktop screens.

## 🚀 How to Run
This is a lightweight, zero-dependency project consisting of single HTML files.

1.  **Download:** Clone this repo or download the ZIP.
2.  **Run:** Simply double-click `index.html` (English) or `ar.html` (Arabic) to open it in your browser.
3.  **Permissions:** Allow "Location Access" when prompted to calculate accurate solar data for your specific coordinates.

## 📂 File Structure
* `index.html` - The English version of the Solar Clock.
* `ar.html` - The Arabic version (RTL support, Eastern Numerals).

## 🛠️ Built With
* HTML5 / CSS3
* [Tailwind CSS](https://tailwindcss.com/) (via CDN)
* Vanilla JavaScript
* [FontAwesome](https://fontawesome.com/) Icons
* [Google Fonts](https://fonts.google.com/)

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
