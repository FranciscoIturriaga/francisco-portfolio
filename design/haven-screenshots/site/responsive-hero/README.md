# Responsive hero (2026-11-05)

Local build (`site/.vercel/output/static`), Playwright, deviceScaleFactor 2, viewport height 900.

- `hero-375.png`: one dark phone, centered (below 640 px).
- `hero-768.png`, `hero-900.png`, `hero-1024.png`: stacked hero, dark and light Home side by side, overlapped, offset, centered (640-1024 px).
- `hero-1440.png`: side by side with the copy, one dark phone (above 1024 px).
- `founding-*.png`, `final-*.png`, `faq-1440.png`: the founding section without numbers, the self-serve final section, the bank-payment FAQ answer.

Checked at each width: no horizontal scroll, no console errors, no layout shift, every visible phone uses a srcset
variant of at least 2x its rendered width, the image keeps its aspect ratio (not cropped), the pair's center is
within 2 px of the viewport center, and no "[" in the visible text.
