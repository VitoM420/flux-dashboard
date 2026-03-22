# FLUX — Influencer Command Center

> A sleek, dark-mode dashboard for influencers to track follower growth, trending hashtags, recent posts, and get actionable growth hints.

![Dashboard Preview](https://img.shields.io/badge/status-live-brightgreen) ![HTML](https://img.shields.io/badge/built%20with-HTML%20%2F%20CSS%20%2F%20JS-FF3D5A) ![Chart.js](https://img.shields.io/badge/charts-Chart.js-F5C842)

---

## ✨ Features

- **📊 Follower Growth Chart** — Interactive line graph with 7D / 30D / 90D toggles
- **🔢 Live Stats Cards** — Followers, engagement rate, reach per post, profile visits
- **# Trending Hashtags** — Searchable panel with HOT / RISING / NEW badges and heat bars. Click to copy any tag instantly
- **📱 Recent Posts Feed** — Caption, hashtags, likes, comments & shares at a glance
- **💡 Growth Hints** — 6 data-backed tips with estimated impact metrics

---

## 🚀 Getting Started

No build step required — it's a single HTML file.

```bash
git clone https://github.com/YOURUSERNAME/flux-dashboard.git
cd flux-dashboard
open index.html   # or just double-click it
```

### Deploy to GitHub Pages

1. Push `index.html` to the `main` branch
2. Go to **Settings → Pages**
3. Set source to **Deploy from branch → main → / (root)**
4. Your dashboard will be live at `https://YOURUSERNAME.github.io/flux-dashboard`

---

## 🛠️ Customisation

All data lives in the `<script>` block at the bottom of `index.html`. Swap in your real numbers:

| Variable | What it controls |
|---|---|
| `chartData` | Follower counts for 7D / 30D / 90D charts |
| `hashtags` | Trending tags, post volumes, heat scores |
| `feedItems` | Recent posts, captions, engagement stats |
| `hints` | Growth tip cards |

To connect live data, wire these to the **Instagram Graph API** or **TikTok Research API** and replace the static arrays with API responses.

---

## 🎨 Tech Stack

- Vanilla **HTML / CSS / JavaScript** — zero dependencies to install
- **[Chart.js](https://www.chartjs.org/)** — growth graph
- **[Google Fonts](https://fonts.google.com/)** — Bebas Neue + DM Sans + JetBrains Mono

---

## 📄 License

MIT — free to use, modify, and share.
