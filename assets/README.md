# Product documentation images

These files support **[`../PRODUCT_README.md`](../PRODUCT_README.md)** (customer-facing). Paths in that document are relative to the `docs/` folder (e.g. `assets/hero-wide.png`).

## Recommended specifications

| File | Role | Suggested size | Notes |
|------|------|----------------|--------|
| `hero-wide.png` | Banner under the title | 1600×500 (or 1200×400) | Brand-aligned dark UI; no third-party logos. |
| `logo-mark.png` | Square mark / social | 512×512 | Simple mark; readable at small sizes. |
| `screenshot-dashboard.png` | Feature section | 1280×720 (16:9) | Real app capture, dark theme. |
| `screenshot-time.png` | Feature section | 1280×720 | Time tab / clock state. |
| `screenshot-money.png` | Feature section | 1280×720 | Money or Finance area. |
| `screenshot-reports.png` | Feature section | 1280×720 | Reports or Work Log. |
| `screenshot-stock.png` | Feature section | 1280×720 | Stock & Supplies. |

## Checklist before a public release

- [ ] Replace illustrative **screenshot-*.png** placeholders with **authentic** screenshots of the shipping build.
- [ ] Re-export **hero-wide.png** if marketing refreshes palette or tagline.
- [ ] Confirm **logo-mark.png** matches your trademark guidelines.
- [ ] Run an accessibility pass: every image in `PRODUCT_README.md` has meaningful **alt** text.

## Optional source art

If your build pipeline already includes `favicon.ico`, `about_page_graphic.jpg`, or `build/branding/Loading.*` (see PyInstaller spec), you may copy derivatives into this folder for a consistent press kit—keep filenames above so links in `PRODUCT_README.md` stay valid.
