<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=700&size=46&pause=1200&color=FFFFFF&center=true&vCenter=true&width=520&height=70&lines=RYU%E3%83%84" alt="RYU" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&pause=1000&color=8A8A8A&center=true&vCenter=true&width=620&height=30&lines=two+wheels+on+the+road%2C+a+headset+on+at+night;valorant+%C2%B7+rank+%C2%B7+settings+%C2%B7+build" alt="tagline" />

<br />

![status](https://img.shields.io/badge/STATUS-LIVE-ffffff?style=flat-square&labelColor=0d0d0d)
![stack](https://img.shields.io/badge/STACK-HTML%20%2F%20CSS%20%2F%20VANILLA%20JS-ffffff?style=flat-square&labelColor=0d0d0d)
![build](https://img.shields.io/badge/BUILD%20STEP-NONE-ffffff?style=flat-square&labelColor=0d0d0d)
![host](https://img.shields.io/badge/HOSTED-GITHUB%20PAGES-ffffff?style=flat-square&labelColor=0d0d0d)

**[ open the site → ](https://itz-ryuu.github.io/site/)**

</div>

---

```text
00 — WHAT THIS IS
```

A single-page profile. Dark, monochrome, type-first. Everything about how I play
and what I play on, in one scroll — no dashboards, no clutter, no tracking.

```text
01 — WHAT'S INSIDE
```

| # | Section | What it holds |
|---|---------|---------------|
| 01 | Who I Am | Short intro, a few numbers |
| 02 | Rank | Current competitive standing |
| 03 | Overview | Main agents and recent form |
| 04 | Settings | Sensitivity, crosshair, video |
| 05 | Build | PC specs and gear |

```text
02 — HOW IT'S MADE
```

- Plain `index.html` shell that boots the page — no framework, no bundler
- All markup, styles and assets tucked away inside `src/`
- Fonts: **Space Grotesk** for display, **JetBrains Mono** for the small caps labels
- Loader with a real progress bar, live clock, scroll-reveal sections, sticky jump nav
- Fully static: clone it, open it, it runs

```text
03 — LAYOUT
```

```text
.
├── index.html          loader shell (the only file at the root)
├── README.md
└── src/
    ├── page.html       every section of the site
    ├── styles.css      the whole design system
    └── assets/
        └── profile.jpg
```

```text
04 — RUNNING IT
```

```bash
git clone https://github.com/Itz-Ryuu/site.git
cd site
python3 -m http.server 8080
# open http://localhost:8080
```

> A local server is needed — `index.html` pulls `src/page.html` at runtime, and
> browsers block that over `file://`.

```text
05 — NOTES
```

- Stats are self-reported and refreshed by hand; treat them as a snapshot, not a feed.
- The design is deliberately restrained: one accent, one grid, a lot of black.
- Everything you see is edited in `src/` — the root never changes.

<div align="center">

<sub>© RYU · built with care</sub>

</div>
