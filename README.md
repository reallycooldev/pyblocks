# ⚡ PyBlocks Studio 2.1

An offline-capable, zero-server **Python 3 IDE, 120-Stage Quad-Course Academy, and Turtle Graphics Playground** built for desktop, tablet, and mobile browsers.

🔗 **Live App:** [reallycooldev.github.io/pyblocks](https://github.io)

---

## ✨ What's New in V2.1
* **⬅️ Prev / Next ➡️ Stage Buttons (`courses.html`):** Jump seamlessly between stages right inside the workspace without scrolling back up to the stage list.
* **💾 Optional Progress Transfer Codes (`PBS_SAVE:`):** Export and import your XP, cleared stages, trophies, and unlocked blueprints across devices using a single portable save string—no accounts or servers required.
* **🎨 `#C0BFBC` Soft Stone Turtle Canvas:** Switched the Turtle drawing surface to a glare-free neutral stone grey so black and colored Turtle strokes stay sharp across every theme.
* **🐢 Revamped Course 2 Section 1:** Replaced repetitive early polygon stages with fast, distinct Turtle challenges (`t.speed(0)`, `penup()`, `circle()`, `dot()`, and a Mini House boss).
* **🛒 New Studio Demo Templates:** Added **Shopping List Price-Checker** and **Classic FizzBuzz (1–30)** to the Free-Build Studio dropdown, and streamlined exports to clean `.py` downloads.

---

## 🚀 Core Features

### 1. 🎓 Quad-Course Academy (`courses.html`)
* **120 Interactive Stages** across 4 structured courses:
  * **Course 1:** Python Fundamentals (48 stages, 6 Section Blueprints)
  * **Course 2:** Turtle Art & Geometry (24 stages, 3 Section Blueprints)
  * **Course 3:** Mini-Game Dev & Spy Ciphers (24 stages, 3 Section Blueprints)
  * **Course 4:** Retro Arcade & Text Adventures (24 stages, 3 Section Blueprints)
* **📖 Explain Function Sandbox:** Interactive beginner reference with live editable Python examples (`print()`, variables, `if/else`, `for` loops, `def()`, `dict{}`, `random`, and `turtle`).

### 2. ⚡ Free-Build Studio (`studio.html`)
* **Multi-File Tabs & Live Syntax Highlighting:** Create, switch, and download multiple `.py` files with line numbers and real-time color highlighting.
* **Mobile Quick-Symbol Bar:** One-tap `Tab`, `()`, `[]`, `{}`, `""`, `:`, and `=` keys for fast coding on touchscreens.
* **🧩 Blueprints & Custom Blocks:** Insert core snippets, Section Boss rewards unlocked from the Academy, or save your own reusable Custom Blocks.
* **🔬 Variable X-Ray & Plain-English Error Tips:** Automatically inspects top-level variables after each run and translates Python tracebacks into beginner-friendly hints.

### 3. 🏆 Progression, Themes & Trophies (`index.html`)
* **8 Rank Titles:** Climb from *Novice Scripter* (`0 XP`) to *PyBlocks Grandmaster* (`3,500+ XP`).
* **12 Trophies:** Includes 9 visible milestones and 3 hidden `???` secret trophies.
* **8 Built-In Themes + Custom Accent Picker:** Switch between *Macchiato, Crimson, Emerald, Amber, Cyber, Ocean, Monochrome,* and *Sunset*, or share custom themes via `PBS2:` codes.

---

## 🛠️ Tech Stack & File Structure
100% static frontend—runs completely offline in any modern browser via **Skulpt**:
* `index.html` — Hub dashboard, stats, theme customizer, `PBS_SAVE:` sync, and trophy showcase
* `courses.html` — 120-stage Quad-Course Academy & Explain Function live sandbox
* `studio.html` — Multi-file Python IDE, Turtle playground, Blueprints & Variable X-Ray
* `skulpt.min.js` & `skulpt-stdlib.js` — Client-side Python 3 interpreter & Turtle engine
