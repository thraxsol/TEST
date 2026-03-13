# thrax • README

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/thraxsol/TEST@main/assets/snake.svg" width="720" alt="Animated snake trail (thrax • serpent)">
</p>

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/thraxsol/TEST@main/assets/serpent-advanced.svg" width="900" alt="thrax • serpent — advanced">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ANIMATION-SVG-111827?style=for-the-badge&logo=svg&logoColor=white" />
  <img src="https://img.shields.io/badge/STYLE-gradient-111827?style=for-the-badge" />
</p>

A lightweight, animated SVG that runs directly in the README via the raw GitHub URL. The image above is served from the repository at `assets/snake.svg` and animates using SMIL/CSS when GitHub loads the raw SVG.

---

### How it works

- The README references the **raw** SVG URL so GitHub serves the file directly and preserves the animation.
- The SVG file must be **committed** to the branch you reference (here: `main` → `assets/snake.svg`).
- Use the `<img>` tag with the raw URL to control display size (`width` or `height`).

---

### Embed snippet (copy this into your README)

```html
<!-- animated SVG served from raw.githubusercontent.com -->
<p align="center">
  <img src="https://raw.githubusercontent.com/thraxsol/TEST/refs/heads/main/assets/snake.svg" width="720" alt="Animated snake trail (thrax • serpent)">
</p>
