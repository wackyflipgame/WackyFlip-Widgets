# 🧩 WackyFlip-Widgets

**Embeddable Mini-Widgets for wackyflip.com**

`WackyFlip-Widgets` provides a suite of **lightweight, embeddable UI components** that power dynamic features on [wackyflip.com](https://wackyflip.com/). These widgets showcase **leaderboards, promotional banners, and interactive game previews**, giving players real-time updates and interactive content across the site.

---

## ✨ Features

| Feature                    | Description                                                                              |
| -------------------------- | ---------------------------------------------------------------------------------------- |
| 🏆 **Leaderboard Widgets** | Real-time global, regional, or clan-based ranking displays                               |
| 🎉 **Promo Banners**       | Rotating banners for events, sales, and featured games                                   |
| 🎮 **Game Previews**       | Interactive previews of new or popular games (e.g., flip mechanics demos)                |
| 📱 **Responsive Design**   | Optimized for desktop, tablet, and mobile views                                          |
| 🔗 **Embed Anywhere**      | Widgets can be embedded across landing pages, blogs, or community hubs                   |
| ⚡ **Live Updates**         | Powered by APIs for instant refresh without full page reloads                            |
| 🧩 **Integration Ready**   | Works seamlessly with `WackyFlip-Newsfeed`, `WackyFlip-Tournaments`, and `WackyFlip-SEO` |

---

## 🛠 Tech Stack

* **Frontend:** React + TailwindCSS (lightweight, responsive components)
* **Backend APIs:** Node.js + GraphQL/REST (fetch leaderboard, promo, and game data)
* **Real-Time:** WebSockets for live leaderboard updates
* **Deployment:** Vercel / Netlify for CDN-based widget hosting

---

## 📁 Repository Structure

```
WackyFlip-Widgets/
├── src/
│   ├── components/
│   │   ├── LeaderboardWidget.tsx
│   │   ├── PromoBanner.tsx
│   │   └── GamePreview.tsx
│   ├── hooks/
│   ├── utils/
│   └── index.ts
├── public/
│   └── assets/
│       └── placeholder.png
├── examples/
│   └── widget-embed.html
└── README.md
```

---

## 🚀 Getting Started

1. Clone the repo:

```bash
git clone https://github.com/wackyflipgame/WackyFlip-Widgets.git
cd WackyFlip-Widgets
npm install
```

2. Run the dev environment:

```bash
npm run dev
```

3. Embed a widget in your site:

```html
<div id="leaderboard-widget"></div>
<script src="https://cdn.wackyflip.com/widgets/leaderboard.js"></script>
<script>
  WackyFlipWidgets.renderLeaderboard("leaderboard-widget", { limit: 10 });
</script>
```

---

## 🔄 Example Promo Banner Config

```json
{
  "id": "promo_summer2025",
  "title": "🔥 Summer Flip Fest!",
  "image": "/assets/promo/summer.png",
  "cta": "Play Now",
  "url": "https://wackyflip.com/events/summerfest"
}
```

---

## 📬 Contribution Guidelines

* Keep widgets **lightweight** (<50kb each where possible)
* Follow **accessibility best practices** (WCAG 2.1 AA)
* Ensure **mobile-first responsiveness**
* Write **unit tests** for live data refresh and embedding behavior

---

## 🔗 Related Repositories

* [`WackyFlip-Newsfeed`](https://github.com/wackyflipgame/WackyFlip-Newsfeed) – Provides data for event announcements
* [`WackyFlip-Tournaments`](https://github.com/wackyflipgame/WackyFlip-Tournaments) – Supplies live tournament leaderboard data
* [`WackyFlip-SEO`](https://github.com/wackyflipgame/WackyFlip-SEO) – Ensures widgets are optimized for search & previews

---

## 📜 License

MIT © 2025 Wacky Flip Studios
