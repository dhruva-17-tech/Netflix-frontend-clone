# 🎬 Netflix-Frontend-Clone

[![React Version](https://img.shields.io/badge/React-v18.x-61dafb?logo=react&logoColor=black)](https://react.dev/)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen)](https://github.com/dhruva-17-tech/Netflix-frontend-clone)

A high-fidelity frontend replica of the Netflix streaming platform built with React. This project focuses on pixel-perfect UI execution, responsive layout design across varying screen breakpoints, and consumption of live entertainment metadata via third-party APIs.

---

## ⚡ Features

- **Dynamic Hero Banner:** Displays a randomly selected trending movie on page refresh with an automated description snippet.
- **Asynchronous Movie Rows:** Categories (Trending, Top Rated, Action, Comedy, Horror, etc.) that fetch real-time media assets asynchronously.
- **Interactive Video Previews:** Clicking on a movie card dynamically searches for and injects the corresponding official YouTube trailer inside a modular tray overlay.
- **Immersive Netflix Styling:** Implements the signature Netflix dark interface layout, custom scrollbar tracks, and smooth CSS hardware-accelerated hover scaling effects.

---

## 🛠️ Tech Stack & Libraries

- **Framework:** React.js (Component-driven architecture)
- **Data Fetching:** Axios (configured with automated base-URL instance routing)
- **API Integration:** TMDB (The Movie Database) REST API 
- **Media Playback:** `react-youtube` & `movie-trailer` for dynamic stream routing

---

## 📂 Project Structure

```text
Netflix-frontend-clone/
├── public/              # Static layout configurations & web icons
└── src/
    ├── components/      # Core reusable UI building blocks
    │   ├── Nav.js       # Sticky dynamic navbar with scroll-fade effects
    │   ├── Banner.js    # Cinematic top billboard hero module
    │   └── Row.js       # Asynchronous scrolling movie categories
    ├── api/             # TMDB axios structural endpoints config
    ├── App.js           # Target rendering point & route controller
    ├── index.js         # Virtual DOM entry point
    └── App.css          # Global overrides & Netflix interface variables
```
🚀 Local Installation & Setup
Follow these steps to run the application interface locally on your machine.

Prerequisites
Make sure you have Node.js (v18+) installed. You will also need an API key from The Movie Database (TMDB).

1. Clone the Repository
  git clone [https://github.com/dhruva-17-tech/Netflix-frontend-clone.git](https://github.com/dhruva-17-tech/Netflix-frontend-clone.git)
  cd Netflix-frontend-clone

2. Environment Configuration
  Create a .env file in the root directory of the project to securely house your TMDB credentials:
  REACT_APP_TMDB_API_KEY=your_tmdb_api_key_here

3. Install Dependencies & Launch
   npm install
   npm start

The application will boot up automatically in your browser at http://localhost:3000.

📄 License
This project is open-source and available under the MIT License.
