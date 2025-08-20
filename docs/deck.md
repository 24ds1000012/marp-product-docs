---
marp: true
theme: product-docs
size: 16:9
paginate: true
math: true
class: lead
backgroundColor: #0b1020
---

<!-- _class: lead -->
# Product Documentation Deck

**A maintainable Marp-based presentation**

**Author:** Technical Writing — 24ds1000012@ds.study.iitm.ac.in

> Version-controlled, reproducible, and exportable to HTML/PDF/PPTX

---

## Why Marp for Product Docs?

- Single **Markdown** source → export to **HTML / PDF / PPTX**
- Fully **version-controlled** in Git (diffable, reviewable)
- **Custom theme** + CSS variables for brand alignment
- **Math**, **code highlighting**, and **background images**

**Build commands** (run from repo root):

```bash
# HTML
npx @marp-team/marp-cli docs/deck.md -o dist/deck.html --allow-local-files

# PDF (requires Chrome/Chromium installed)
npx @marp-team/marp-cli docs/deck.md -o dist/deck.pdf --allow-local-files

# PowerPoint
npx @marp-team/marp-cli docs/deck.md -o dist/deck.pptx --allow-local-files
