# PyBlocks Studio — Project Context & Rules
- **Creator:** Aiden Austin (Year 7 student, Carine SHS, mobile/tablet workflow using Spck Editor + GitHub + Cloudflare Workers).
- **Live URL:** https://workers.dev | **Repo:** ://github.com
- **Current Version:** V2.2 (~80KB total across 3 static vanilla HTML/CSS/JS files + Skulpt + README.md).
- **Architecture & Files:**
  1. `index.html`: Hub dashboard, 8 themes + custom accent (`PBS2:` Base64 theme sharing), `PBS_SAVE:` Base64 progress transfer (`localStorage` key `"pbs_v2"`), 8 ranks, 18 trophies (13 visible + 5 secret `???`), and milestone auto-sync.
  2. `studio.html`: Multi-file Python 3 IDE (`localStorage` key `"pbs_v2_files"`), layered `<textarea>` + `<pre>` regex syntax highlighter, mobile quick-symbol bar, `#C0BFBC` Turtle canvas, 7 demos, Blueprints + Custom Blocks (with `✕` delete), Variable X-Ray, and `.py` download.
  3. `courses.html`: 120-stage Quad-Course Academy (Course 1: 48 stages; Courses 2–4: 24 stages each), `⬅️ Prev` / `Next ➡️` stage buttons, `✅` course completion badges, real `#tcanvas` Turtle validator for Course 2, `BOSS 3.8: Neon Fireworks`, and `Explain Function` live sandbox.
- **Coding & Formatting Rules for Responses:**
  - Always deliver full, copy-pasteable code split into **80–100 line boxes** (up to 3 boxes per message) for easy pasting in Spck Editor on mobile.
  - Never use raw numeric array indexing like `arr[0]` or `arr[1]` in JS snippets—always use `.at(0)`, `.at(1)`, etc., so markdown formatters don't strip bracketed numbers.
