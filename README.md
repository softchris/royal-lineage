# 👑 Royal Lineage — From Gustaf Vasa to the Present

An interactive, single-page genealogy website tracing a Swedish royal lineage across **17 generations** — from King Gustaf I Eriksson Vasa (1496) to the present day.

🌐 **Live site:** [https://softchris.github.io/royal-lineage/](https://softchris.github.io/royal-lineage/)

---

## ✨ Features

- **Interactive Family Tree** — Click any ancestor to zoom in and explore their life events
- **Vertical Timeline Ruler** — Per-person timeline showing birth, death, and key historical events with adaptive spacing
- **Bookmark-style Event Tabs** — Clickable event cards on desktop (alternating left/right) and mobile (compact bookmarks)
- **Century Music** — Epoch-appropriate ambient music that changes as you navigate through the centuries
- **Chronicle Modals** — Rich biographical narratives with Wikipedia-sourced content for each person
- **Narration** — Text-to-speech narration of each person's chronicle
- **Search** — Find any ancestor by name or keyword
- **Bilingual** — Full English and Swedish language support with one-click toggle
- **Fully Responsive** — Optimized for desktop, tablet, and mobile with hamburger menu navigation
- **Single File Architecture** — The entire application lives in one `index.html` file — no build tools, no dependencies

## 🏰 The Lineage

The tree traces a direct ancestral line through Swedish history:

| # | Person | Era |
|---|--------|-----|
| 1 | **Gustaf I Eriksson Vasa** | 1496–1560 |
| 2 | Erik XIV | 1533–1577 |
| 3 | Gustaf Eriksson | 1568–1607 |
| 4 | Gustaf Gustafsson af Vasaborg | 1616–1653 |
| 5–17 | *...through 13 more generations...* | 1600s–present |

Each person includes life events, historical context, and connections to Swedish and European history — from the Stockholm Bloodbath (1520) to modern times.

## 🚀 Getting Started

No build step required. Just open the file:

```bash
# Clone the repo
git clone https://github.com/softchris/royal-lineage.git
cd royal-lineage

# Open in your browser
open index.html
# or on Windows
start index.html
```

Or visit the [live GitHub Pages site](https://softchris.github.io/royal-lineage/).

## 🛠 Tech Stack

- **Pure HTML/CSS/JavaScript** — no frameworks, no dependencies
- **SVG** — dynamically generated family tree visualization
- **CSS Custom Properties** — dark gold-accented theme
- **Web Audio API** — epoch-appropriate background music
- **Web Speech API** — text-to-speech narration
- **Responsive Design** — mobile-first with desktop enhancements

## 📱 Mobile Experience

- Hamburger menu with Home, Lineage, Search, and Language options
- Compact bookmark-style event tabs with gold glow for contrast
- Touch-friendly tap targets
- Fixed audio controls (top-left)
- Vertical timeline ruler (right side)

## 🖥 Desktop Experience

- Full navigation bar with smooth scroll
- Alternating left/right event bookmark tabs aligned to viewport edges
- Hover tooltips on tree nodes
- Instructional hints for first-time visitors
- Timeline ruler with graduated tick marks

## 📄 License

This project is open source. Genealogical data draws on *Ättlingar till Gustav I och hans bröder samt systrar* by Per Andersson, together with linked reference sources such as Wikipedia and Adelsvapen.
