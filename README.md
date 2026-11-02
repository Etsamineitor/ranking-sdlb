# 🏆 SDLB Official Leaderboard (2020-2026)

A dynamic, web-based statistics application designed to display live standings, player scores, rank trend shifts, and 3D Minecraft avatars for the official **SDLB** tournament.

---

## 🌐 Live Demo & Deployment Workflow
- **Live Leaderboard:** 👉 **(https://github.com/Etsamineitor)(https://cheerful-liger-7de6ac.netlify.app/)**
- **Continuous Updates:** The source code in this repository serves as the core foundation of the application. As tournament rounds progress, score adjustments and structure enhancements pushed here are reflected directly on the live deployed site to maintain real-time accuracy for spectators.

---

## ✨ Key Features
- **Real-Time Standings:** Automatic sorting by score, highlighting the top 3 podium finishers with custom medal indicators.
- **Dynamic Trend Shift:** Visually tracks player movement across the leaderboard using color-coded numerical shift indicators.
- **3D Player Avatars:** Fetches authenticated Minecraft player head skins dynamically via the MC-Heads API.
- **Instant Search:** Client-side filter allowing users to query players by username instantly.
- **Responsive UI:** Modern glassmorphism interface powered by Tailwind CSS, tailored for all device viewports.

---

## 🛠️ Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Styling & Icons:** [Tailwind CSS](https://tailwindcss.com/) (CDN), [Font Awesome 6](https://fontawesome.com/)
- **API:** [MC-Heads API](https://mc-heads.net/)
- **Deployment:** Netlify

---

## 📁 Repository Architecture
```text
├── index.html       # Clean spectator view (Deployed read-only interface)
└── admin.html       # Local administrative control panel for dynamic score management
