# Saptabandhan — Prarthana & Yatin Wedding Invitation (Bride Side)

A rich, interactive digital wedding invitation website built with **React**, **Vite**, and **Tailwind CSS v4**. Designed specifically for the **Bride Side (Bhatt Family)** based on the traditional Indian wedding theme and "Saptabandhan" concept.

---

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev      # http://localhost:5173

# Build for production
npm run build    # Compiled assets generated in dist/

# Preview production build locally
npm run preview
```

---

## ✨ Features & Structure

- **Interactive Envelope Opening (`Intro.jsx`):**
  - Realistic interactive envelope with sealed wax badge and marigold flower burst animation.
  - Centered tap-to-open medallion button with smooth audio initiation.
- **Audio Background Player (`MusicPlayer.jsx`):**
  - Seamless background wedding soundtrack (*Sajna*), auto-playing upon user interaction with floating play/pause controls.
- **Smooth Page Scrolling:**
  - Eased inertia scrolling powered by **Lenis** with right-side navigational tracking dots (`NavDots.jsx`).
- **Wedding Journey Sections:**
  1. **Shri Ganesh:** Auspicious Gujarati Shloka, traditional border frame, and family intro.
  2. **Monogram:** Animated monogram crest for *Prarthana & Yatin*.
  3. **Saptabandhan:** Seven sacred wedding journey chapters detailing spiritual elements and wedding rituals.
  4. **Event Pages:**
     - **Chundadi** — *The Royal Life (Rajputana Theme)*
     - **Mehandi** — *The Garden of Love (Mughal Garden Theme)*
     - **Grah Shanti** — *Sacred Blessings (Temple Theme)*
     - **Haldi** — *The Roots of Love (Village Mela Theme)*
     - **Sangeet** — *Walking to the Moon (Sufi Galaxy Theme)*
     - **Wedding / Hastmelap** — *Eternity (Sacred Agni Theme)*
  5. **Family Invitation:** Cordial invitation from the Bhatt family with traditional respectful titles.

---

## 🎨 Theme & Typography

- **Date Formatting:** Automatic superscript formatting for date suffixes (`st`, `nd`, `rd`, `th`).
- **Dynamic Theming (`ThemeDecor.jsx`):** Dedicated SVG background ornaments (mandap arches, floral garlands, candles, crescent moon and Sufi stars) per event.
- **Typography:** Custom Gujarati (`font-gujarati`) and Devanagari (`font-devanagari`) fonts for mantras and shlokas.

---

## 🛠️ Configuration & Content

All text, event timings, venues, dress codes, mantras, and family members are organized cleanly in:
- `src/data/content.js`

### 🔧 Dev URL Parameters:
- `?skipIntro=true` — Skips the envelope intro directly to the first invitation card.
- `?introAt=2500` — Freezes the envelope animation at a specific millisecond timestamp for styling.