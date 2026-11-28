# PyBlocks Studio — Project Context & Rules
- **Creator:** Aiden Austin (Year 7 student, Carine SHS, mobile/tablet workflow using Spck Editor + GitHub + Cloudflare Workers).
- **Live URL:** https://workers.dev | **Repo:** ://github.com
- **Current Version:** V2.3 (~81KB total across 3 static vanilla HTML/CSS/JS files + Skulpt + README.md).
- **Architecture & Files:**
  1. `index.html`: Hub dashboard, 8 themes + custom accent (`PBS2:` Base64 theme sharing), `PBS_SAVE:` Base64 progress transfer (`localStorage` key `"pbs_v2"`), 8 ranks (max `3,525 XP` = PyBlocks Grandmaster), 18 trophies (13 visible + 5 secret `???`), and milestone auto-sync.
  2. `studio.html`: Multi-file Python 3 IDE (`localStorage` key `"pbs_v2_files"`), layered `<textarea>` + `<pre>` regex syntax highlighter, smart auto-indent + `else:`/`elif`/`except:` auto-outdent, mobile quick-symbol bar with `⇤ Tab` un-indent, `#C0BFBC` Turtle canvas, 7 demos, Blueprints + Custom Blocks (with `✕` delete), Variable X-Ray, `⚡ Ran in Xms` execution timer, and `Blob` + clipboard `.py` download.
  3. `courses.html`: 120-stage Quad-Course Academy (Course 1: 48 stages; Courses 2–4: 24 stages each; `3,525 XP` total), `⬅️ Prev` / `Next ➡️` stage buttons, `✅` course completion badges, real `#tcanvas` Turtle validator for Course 2, `BOSS 3.8: Neon Fireworks`, smart auto-indent + `⇤ Tab`, and contextual per-stage `📖 Explain: <topic>` button wired to a 15-topic live sandbox.
- **Coding & Formatting Rules for Responses:**
  - Deliver code in small, focused patches or **~40–80 line boxes** for easy pasting in Spck Editor on mobile.
  - Never use raw numeric array indexing like `arr` or `arr` in JS snippets (use `.at(0)`, `Array.of(...)`, or `list((...))` in Python strings) so markdown formatters never strip bracketed numbers.
