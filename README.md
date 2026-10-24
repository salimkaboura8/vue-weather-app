<div align="center">

# ☀️ Vue Weather App

**A simple, clean weather app for any city, built with Vue.js**

![Vue.js](https://img.shields.io/badge/Vue-2-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![OpenWeatherMap](https://img.shields.io/badge/OpenWeatherMap-EB6E4B?style=for-the-badge)

[📂 Source](src) · [🖼️ App Component](src/App.vue)

</div>

---

## 📖 Overview

A single-page **Vue.js** app that shows the current weather for any city. Type a city name and press **Enter** to see the temperature, the conditions and today's date. The background switches to a warm theme when it's above 16 °C.

## 🔄 How It Works

| Step | What happens |
|:---:|---|
| 1️⃣ | The user types a city name in the search bar and presses **Enter** |
| 2️⃣ | The app calls the **OpenWeatherMap** current-weather endpoint (metric units) |
| 3️⃣ | The response shows the location, country, temperature and conditions |
| 4️⃣ | The background changes based on the temperature |

## ✨ Highlights

| 🌐 Data | 🎨 UI | ⚙️ Setup |
|---|---|---|
| OpenWeatherMap API<br>Native `fetch`<br>Celsius temperatures | Search on Enter<br>Warm / cold backgrounds<br>Formatted date | Vue CLI<br>ESLint<br>Single-file component |

## 🚀 Quick Start

```bash
git clone https://github.com/salimkaboura8/vue-weather-app.git
cd vue-weather-app

npm install
npm run serve
```

> 🔑 Put your own OpenWeatherMap API key in `src/App.vue` (`api_key`).

---

<div align="center">
Made with ❤️ by <a href="https://github.com/salimkaboura8">Salim Kaboura</a>
</div>
