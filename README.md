# SiNES Calculator — Standalone Page

**Sinonasal iNflammation Endoscopic Score**  
Developed at St. Paul's Sinus Centre, Vancouver, BC

---

## Files in this folder

| File | Description |
|------|-------------|
| `index.html` | Bilingual (EN/ES) standalone SiNES calculator page |
| `stpauls-logo.webp` | St. Paul's Sinus Centre logo |

---

## How to deploy on GitHub

Place the `sines/` folder in the **root** of your existing GitHub repository, alongside your `en.html`, `es.html`, and `index.html`:

```
your-repo/
├── index.html          ← updated (links to sines/)
├── en.html             ← updated (SiNES tab now opens sines/index.html)
├── es.html             ← updated (SiNES tab now opens sines/index.html)
├── sines/
│   ├── index.html      ← standalone bilingual SiNES calculator
│   └── stpauls-logo.webp
└── ... (other files)
```

The standalone page URL will be:  
`https://yourusername.github.io/your-repo/sines/`

---

## Features

- **Bilingual** — English / Spanish with a single toggle (auto-detects browser language on load)
- **St. Paul's logo** in the header
- **YouTube instructional video** displayed on the right of the intro section
- **Full SiNES calculator** with all 5 anatomical sites, 3 subdomains, N/A checkboxes, and polyp extension grading
- **Score conversions** to MLK, NPS, and DIP after calculation
- **Back to site** link in the header returns to `../index.html`
- **Reference & download link** to the original paper (DOI: 10.4193/Rhin23.434)

---

## Reference

Hernaiz-Leonardo JC, et al.  
*"Development and validation of the Sinonasal Endoscopic Score (SiNES) for chronic rhinosinusitis."*  
**Rhinology** 62(4), 2024.  
DOI: [10.4193/Rhin23.434](https://doi.org/10.4193/Rhin23.434)
