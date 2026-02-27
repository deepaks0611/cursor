# Cursor.com – Landing Page Clone

A pixel-faithful static HTML/CSS clone of the [Cursor](https://cursor.com) homepage.

---

## 📁 Project Structure

```
cursor-clone/
├── index.html
├── style.css
└── images/
    ├── favicon.jpg
    ├── cursor-logo.png
    ├── auto-code-img.jpg
    ├── stripe-logo.svg
    ├── openai-logo.svg
    ├── linear-logo.svg
    ├── datadog-logo.svg
    ├── nvidia-logo.svg
    ├── figma-logo.svg
    ├── ramp-logo.svg
    ├── adobe-logo.svg
    ├── learn-about-agent.jpg
    ├── learn-about-tab.jpg
    ├── learn-about-cursor-ecosystem.jpg
    ├── diana-hu.webp
    ├── shadcn.webp
    ├── andrej-karpathy.webp
    ├── patrick-collison.webp
    ├── theprimeagen.webp
    ├── greg-brockman.webp
    ├── explore-models.jpg
    ├── explore-indexing.jpg
    ├── explore-enterprise.webp
    ├── research-team.webp
    └── ...
```

---

## 🚀 Getting Started

No build tools needed. Just open `index.html` in your browser:

```bash
# Option 1 — Direct open
open index.html

# Option 2 — Local server (recommended)
npx serve .

# Option 3 — Python server
python3 -m http.server 8000
```

Then visit `http://localhost:8000`

---

## 🎨 Design Tokens (CSS Variables)

| Variable                | Value       | Usage                        |
|-------------------------|-------------|------------------------------|
| `--text-color`          | `#EDECEC`   | Primary text                 |
| `--text-bg-color`       | `#14120B`   | Main background              |
| `--btn-bg-hover-color`  | `#edecece8` | Button hover state           |
| `--logo-bg-color`       | `#1B1913`   | Card / section backgrounds   |
| `--text-box-p-color`    | `#999691`   | Muted / secondary text       |
| `--text-box-btn-color`  | `#EE4E00`   | Orange accent links/buttons  |

---

## 🧩 Page Sections

| Section                  | Class / Element                      | Description                              |
|--------------------------|--------------------------------------|------------------------------------------|
| **Navbar**               | `.web-header`                        | Sticky top nav with logo, links, buttons |
| **Hero**                 | `.auto-code-container`               | Headline, CTA button, hero image         |
| **Trusted By**           | `.companies-logo-container`          | 8 company logos in a row                 |
| **Agent Feature**        | `.learn-about-agent-container` (×3)  | 3 alternating image + text rows          |
| **Testimonials**         | `.whole-software-section`            | 6 quote cards in a 3×2 grid              |
| **Stay on Frontier**     | `.frontier-container`                | 3 feature cards with images              |
| **Changelog**            | `.changelog-container`               | 4 recent changelog entries               |
| **Research Team**        | `.research-team-container`           | Team photo + join CTA                    |
| **Recent Highlights**    | `.recent-highlight-container`        | 3 blog post links                        |
| **Download CTA**         | `.try-cursor-content`                | Large "Try Cursor now" section           |
| **Footer**               | `.cursor-footer-container`           | 5-column links grid                      |

---

## 🔧 Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Grid, Flexbox, CSS Variables
- **Font Awesome 7** — Icons (arrow-down, arrow-right)
- **Google Fonts** — Inter
- **No JavaScript** — Pure static page

---

## 📱 Layout Notes

- Navbar is `position: sticky` so it stays at the top on scroll
- Feature sections use `display: grid` with `repeat(2, 1fr)` for image + text layout
- Testimonial cards use `repeat(3, 1fr)` 3-column grid
- Footer uses `repeat(5, 1fr)` 5-column grid
- All card backgrounds use `--logo-bg-color` (`#1B1913`) on top of `--text-bg-color` (`#14120B`)

---

## 📄 License

This is a **UI clone for learning/portfolio purposes only** and is not affiliated
with or endorsed by Cursor / Anysphere Inc. All branding and content belong to
[Anysphere Inc](https://cursor.com).
