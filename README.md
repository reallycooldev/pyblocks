# ⚡ PyBlocks Studio 2.3

An offline-capable, zero-server **Python 3 IDE, 120-Stage Quad-Course Academy, and Turtle Graphics Playground** built for desktop, tablet, and mobile browsers.

🔗 **Live App:** [pyblocks-studio.aiden-austin.workers.dev](https://workers.dev)

---

## ✨ What's New in V2.3
* **⌨️ Smart Python Auto-Indent & `⇤ Tab` Un-Indent (`studio.html` & `courses.html`):** Pressing `Enter` automatically keeps indentation inside blocks, indents 4 spaces after `:`, auto-outdents `else:` / `elif` / `except:`, and adds a one-tap **`⇤ Tab`** un-indent key to the mobile bar.
* **📖 Contextual Stage `Explain` Button & 15-Topic Sandbox (`courses.html`):** Each stage now displays a tailored **`📖 Explain: <topic>`** button that opens the live sandbox straight to the operator or function used in that stage (expanded from 8 to 15 interactive topics including `// & %`, `min / max`, `[::-1]`, `.join()`, `chr & ord`, and `try/except`).
* **⚡ Live Execution Timer & Upgraded `.py` Export (`studio.html`):** Displays script run speed (`⚡ Ran in Xms`) in the console header and upgrades **Download `.py`** to use a real `Blob` download alongside automatic clipboard copy backup.
* **🎯 Smoothed Course 3 Curve & Starter Fixes (`courses.html`):** Reordered Course 3 Section 3 for smoother progression and fixed list starter templates across Courses 3 & 4.

---

## 🚀 Core Features

### 1. 🎓 Quad-Course Academy (`courses.html`)
* **120 Interactive Stages (`3,525 XP` total)** across 4 structured courses with **`⬅️ Prev` / `Next ➡️`** navigation and **`✅`** course completion badges:
  * **Course 1:** Python Fundamentals (48 stages, 6 Section Blueprints)
  * **Course 2:** Turtle Art & Geometry (24 stages, 3 Section Blueprints, real canvas validation)
  * **Course 3:** Mini-Game Dev & Spy Ciphers (24 stages, 3 Section Blueprints)
  * **Course 4:** Retro Arcade & Text Adventures (24 stages, 3 Section Blueprints)
* **📖 Per-Stage Explain Sandbox:** 15 live editable Python examples covering every core operator and data structure in the curriculum.

### 2. ⚡ Free-Build Studio (`studio.html`)
* **Multi-File Tabs & Live Syntax Highlighting:** Create, switch, and export multiple `.py` files with line numbers and real-time color highlighting.
* **Mobile Quick-Symbol Bar:** One-tap `Tab`, `⇤ Tab`, `()`, `[]`, `{}`, `""`, `:`, and `=` keys paired with smart auto-indent.
* **🧩 Blueprints & Custom Blocks:** Insert core snippets, Section Boss rewards unlocked from the Academy, or create and delete your own reusable Custom Blocks.
* **🔬 Variable X-Ray, Execution Timer & Plain-English Error Tips:** Inspects top-level variables after each run, times execution in milliseconds, and translates Python tracebacks into beginner-friendly hints.

### 3. 🏆 Progression, Themes & Sync (`index.html`)
* **8 Rank Titles:** Climb from *Novice Scripter* (`0 XP`) to *PyBlocks Grandmaster* (`3,500+ XP`, max `3,525 XP`).
* **18 Trophies:** Includes 13 visible milestones and 5 hidden `???` secret trophies.
* **8 Built-In Themes + Custom Accent Picker:** Switch between *Macchiato, Crimson, Emerald, Amber, Cyber, Ocean, Monochrome,* and *Sunset*, or share custom themes via `PBS2:` codes.
* **💾 Portable Progress Transfer (`PBS_SAVE:`):** Back up or sync your stages, XP, trophies, blueprints, and custom blocks across devices with zero servers or accounts.

---

## 🛠️ Tech Stack & File Structure
100% static frontend—runs completely offline in any modern browser via **Skulpt**:
* `index.html` — Hub dashboard, stats, theme customizer, `PBS_SAVE:` sync, and 18-trophy showcase
* `courses.html` — 120-stage Quad-Course Academy & 15-topic Explain Function live sandbox
* `studio.html` — Multi-file Python IDE, `#C0BFBC` Turtle playground, Blueprints, Execution Timer & Variable X-Ray
* `skulpt.min.js` & `skulpt-stdlib.js` — Client-side Python 3 interpreter & Turtle engine
