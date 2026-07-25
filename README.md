<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2196F3,100:21CBF3&height=180&section=header&text=IP%20Tracker&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Real-Time%20IP%20Address%20Geolocation%20Tracker&descAlignY=60&descSize=16" width="100%"/>

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![API](https://img.shields.io/badge/Geolocation-API-2196F3?style=for-the-badge)](#)

> A **real-time IP address geolocation tracker** that resolves any IP address or domain to its geographic location, ISP, and timezone — built with vanilla JavaScript and a geolocation API.

</div>

---

## 📋 About This Project

**IP Tracker** is a clean, minimal web application that allows users to enter any IP address or domain name and instantly retrieve detailed geolocation data. The results are displayed on an interactive map with key network and location details.

---

## ✨ Features

- 🌍 **Real-Time Geolocation** — Resolve IP addresses to precise coordinates
- 🗺️ **Interactive Map** — Visualize IP location on an embedded map
- 📡 **ISP & Network Info** — Display internet provider and ASN details
- 🕐 **Timezone Detection** — Show local timezone for the IP's region
- ⚡ **Instant Search** — Fast API-driven lookups with no page reload
- 📱 **Responsive Design** — Works seamlessly on all screen sizes

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure |
| **CSS3** | Styling and responsive layout |
| **JavaScript (ES6+)** | API calls, DOM updates, map integration |
| **IP Geolocation API** | IP-to-location data provider |
| **Leaflet.js / Maps** | Interactive map rendering |

---

## 📁 Project Structure

```
iptracker/
├── code                  # Application source files
│   ├── index.html        # Main page layout
│   ├── style.css         # Responsive styling
│   └── script.js         # API fetch logic and map updates
```

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/Devansh8954/iptracker.git
cd iptracker/code

# Open in browser
# Double-click index.html, or use Live Server in VS Code
```

> **Note:** You may need a free API key from [ipify](https://www.ipify.org/) or [ip-api.com](http://ip-api.com/). Add your key to `script.js` where the API URL is defined.

---

## 💡 How It Works

```
User enters IP / Domain
        │
        ▼
  fetch() → Geolocation API
        │
        ▼
  Parse JSON response
   (IP, city, country, ISP, timezone, lat/lng)
        │
        ▼
  Update DOM cards with info
        │
        ▼
  Pan map to coordinates & drop marker
```

---

## 📊 Data Returned

| Field | Example |
|---|---|
| **IP Address** | 192.168.0.1 |
| **Location** | Mumbai, Maharashtra, IN |
| **Timezone** | UTC +05:30 |
| **ISP** | Reliance Jio |
| **Coordinates** | 19.0760° N, 72.8777° E |

---

<div align="center">

**Built with ❤️ by [Devansh Tyagi](https://github.com/Devansh8954)**

⭐ Star this repo if you found it useful!

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2196F3,100:21CBF3&height=100&section=footer" width="100%"/>

</div>
