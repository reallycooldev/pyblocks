# ⚡ PyBlocks Studio 2.2

An offline-capable, zero-server **Python 3 IDE, 120-Stage Quad-Course Academy, and Turtle Graphics Playground** built for desktop, tablet, and mobile browsers.

🔗 **Live App:** [reallycooldev.github.io/pyblocks](https://github.io)

---

## ✨ What's New in V2.2
* **✅ Completed Course Badges (`courses.html`):** Finished Course tabs automatically display a **`✅`** badge and green completion border once all stages in that course are cleared.
* **🏆 Expanded 18-Trophy Showcase (`index.html`):** Added **6 new achievements** (*Halfway Legend*, *Block Smith*, *Blueprint Collector*, *Code Exporter*, plus 2 secret `???` trophies: *Canvas Painter* and *Time Traveler*) alongside automatic milestone syncing for `PBS_SAVE:` codes.
* **🐢 Real Turtle Canvas Validator (`2.1.1` – `2.3.8`):** Removed mandatory `print()` checks across all 24 Course 2 stages—stages now validate directly against real Turtle drawings rendered on `#tcanvas`.
* **🎆 `BOSS 3.8: Neon Fireworks`:** Replaced `Grand Mandala` with a self-explanatory 12-spoke colorful burst shooting out from the center with cycling neon colors.
* **🗑️ Custom Block Delete Buttons (`studio.html`):** Added one-tap red **`✕`** delete buttons to saved Custom Blocks in Free-Build Studio.

---

## 🚀 Core Features

### 1. 🎓 Quad-Course Academy (`courses.html`)
* **120 Interactive Stages** across 4 structured courses with **`⬅️ Prev` / `Next ➡️`** stage navigation and **`✅`** course completion badges:
  * **Course 1:** Python Fundamentals (48 stages, 6 Section Blueprints)
  * **Course 2:** Turtle Art & Geometry (24 stages, 3 Section Blueprints, real canvas validation)
  * **Course 3:** Mini-Game Dev & Spy Ciphers (24 stages, 3 Section Blueprints)
  * **Course 4:** Retro Arcade & Text Adventures (24 stages, 3 Section Blueprints)
* **📖 Explain Function Sandbox:** Interactive beginner reference with live editable Python examples (`print()`, variables, `if/else`, `for` loops, `def ()`, `dict {}`, `random`, and `turtle`).

### 2. ⚡ Free-Build Studio (`studio.html`)
* **Multi-File Tabs & Live Syntax Highlighting:** Create, switch, and download multiple `.py` files with line numbers and real-time color highlighting.
* **Mobile Quick-Symbol Bar:** One-tap `Tab`, `()`, `[]`, `{}`, `""`, `:`, and `=` keys for fast coding on touchscreens.
* **🧩 Blueprints & Custom Blocks:** Insert core snippets, Section Boss rewards unlocked from the Academy, or create and manage your own reusable Custom Blocks.
* **🔬 Variable X-Ray & Plain-English Error Tips:** Automatically inspects top-level variables after each run and translates Python tracebacks into beginner-friendly hints.

### 3. 🏆 Progression, Themes & Sync (`index.html`)
* **8 Rank Titles:** Climb from *Novice Scripter* (`0 XP`) to *PyBlocks Grandmaster* (`3,500+ XP`).
* **18 Trophies:** Includes 13 visible milestones and 5 hidden `???` secret trophies.
* **8 Built-In Themes + Custom Accent Picker:** Switch between *Macchiato, Crimson, Emerald, Amber, Cyber, Ocean, Monochrome,* and *Sunset*, or share custom themes via `PBS2:` codes.
* **💾 Portable Progress Transfer (`PBS_SAVE:`):** Back up or sync your stages, XP, trophies, blueprints, and custom blocks across devices with zero servers or accounts.

---

## 🛠️ Tech Stack & File Structure
100% static frontend—runs completely offline in any modern browser via **Skulpt**:
* `index.html` — Hub dashboard, stats, theme customizer, `PBS_SAVE:` sync, and 18-trophy showcase
* `courses.html` — 120-stage Quad-Course Academy & Explain Function live sandbox
* `studio.html` — Multi-file Python IDE, `#C0BFBC` Turtle playground, Blueprints & Variable X-Ray
* `skulpt.min.js` & `skulpt-stdlib.js` — Client-side Python 3 interpreter & Turtle engine
