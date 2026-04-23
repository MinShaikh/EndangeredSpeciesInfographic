# 🌍 Wild & Endangered — Interactive Animal Infographic

> A funky, interactive single-page infographic website showcasing three critically endangered species — brought to life with animated SVG icons, live data visualizations, and built-in image downloads.

---

## 🐾 Featured Animals

| Animal | Scientific Name | IUCN Status |
|---|---|---|
| 🐆 Amur Leopard | *Panthera pardus orientalis* | 🔴 Critically Endangered (CR) |
| 🐟 Atlantic Sturgeon | *Acipenser oxyrinchus oxyrinchus* | 🔴 Critically Endangered (CR) |
| 🦅 California Condor | *Gymnogyps californianus* | 🟠 Endangered (EN) |

---

## ✨ Features

- **Tabbed navigation** — switch between animals with smooth spring animations
- **Animated SVG mascots** — each animal has a custom CSS-animated illustration:
  - 🐆 Leopard prowls, tail swishes, spots pulse
  - 🐟 Sturgeon swims side-to-side, fins flap, bubbles float up
  - 🦅 Condor soars on thermals, wings flap, sun pulses behind
- **Animated diet bars** — fill up with a spring bounce on every tab switch
- **Stats cards** — icons wobble on hover
- **Life cycle flows** — visual step-by-step progression for each species
- **Threat breakdowns** — habitat, poaching, climate threats per animal
- **Conservation highlights** — including the Condor's remarkable 27 → 500+ comeback story
- **Download infographics** — embedded high-res PNG images downloadable with one click, with a bounce animation on the button
- **Fully offline** — all images are base64-encoded directly in the HTML; no external assets needed after load

---

## 🗂️ Project Structure

```
wildlife-infographic.html   ← entire project in one self-contained file
README.md                   ← this file
```

No build tools, no dependencies, no frameworks. Just one HTML file.

---

## 🚀 How to Run Locally

1. Download `wildlife-infographic.html`
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. That's it — no server, no install required

```bash
# Or serve it locally with Python if you prefer
python3 -m http.server 8000
# Then open http://localhost:8000/wildlife-infographic.html
```

---

## 🌐 How to Host Live (Free)

### Option 1 — Netlify Drop *(fastest, no account needed)*
1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Drag and drop `wildlife-infographic.html` onto the page
3. Get a live URL instantly (e.g. `https://funky-animals-xyz.netlify.app`)

### Option 2 — GitHub Pages
1. Create a new GitHub repository
2. Upload the file and rename it to `index.html`
3. Go to **Settings → Pages → Source → main branch**
4. Live at `https://yourusername.github.io/your-repo-name`

### Option 3 — Vercel
```bash
npm i -g vercel
vercel
# Follow the prompts — live in ~1 minute
```

### Option 4 — Tiiny.host *(no signup, instant)*
Upload at [tiiny.host](https://tiiny.host) for a temporary shareable link.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, keyframe animations, grid/flexbox) |
| Interactivity | Vanilla JavaScript |
| Icons | Custom inline SVG with CSS animations |
| Fonts | [Fredoka One](https://fonts.google.com/specimen/Fredoka+One), [Boogaloo](https://fonts.google.com/specimen/Boogaloo), [Nunito](https://fonts.google.com/specimen/Nunito) via Google Fonts |
| Images | Base64-encoded PNG (embedded, no external requests) |

---

## 🎨 Design System

### Color Palette

| Animal | Primary | Light | Dark |
|---|---|---|---|
| 🐆 Amur Leopard | `#FF6B35` | `#FFF0EA` | `#C94A1A` |
| 🐟 Atlantic Sturgeon | `#3B82C4` | `#EAF3FB` | `#1B5A99` |
| 🦅 California Condor | `#7C4DBC` | `#F3EDFC` | `#5A2D99` |
| Neutral / BG | `#F7F3EE` | `#FFFDF9` | `#2A2118` |

### Typography
- **Display / Headings** — Fredoka One (funky, rounded)
- **Labels / Badges** — Boogaloo (casual, playful)
- **Body / UI** — Nunito (friendly, readable)

---

## 📸 Infographic Sources

The three downloadable infographics cover:
- **Amur Leopard** — population stats, threats, conservation efforts in Russian Far East
- **Atlantic Sturgeon** — life cycle, habitat, ancient lineage facts
- **California Condor** — the 1987–2024 population comeback story

Data references: [IUCN Red List](https://www.iucnredlist.org) · [Peregrine Fund](https://peregrinefund.org) · [NOAA Fisheries](https://www.fisheries.noaa.gov)

---

## 🤝 How You Can Help

- 🐆 **Amur Leopard** — support [WWF Amur Leopard](https://www.worldwildlife.org/species/amur-leopard) programs
- 🐟 **Atlantic Sturgeon** — support [NOAA Fisheries](https://www.fisheries.noaa.gov/species/atlantic-sturgeon) river restoration
- 🦅 **California Condor** — donate to the [Peregrine Fund](https://peregrinefund.org)

---

## 📄 License

This project is for educational and conservation awareness purposes. Infographic images are sourced from conservation organizations — please credit appropriately when sharing.

---

<p align="center">Made with 💚 for wildlife conservation · Every species counts.</p>
