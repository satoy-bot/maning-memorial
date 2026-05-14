# Kid from Parian — Memorial Site for Manuel "Maning" S. Satorre Jr.

A newspaper-themed memorial / living family archive built around the concept **"The Cross and the Byline"**.

Honoring him as Cebuano lawyer, journalist, editor, columnist, broadcaster, environmental advocate, husband, father, grandfather, and Outstanding Carolinian.

## Status

- **Not deployed.** Local scaffold only as of 2026-05-14.
- Sister site to `production/memorial-victoria-satorre/` (deployed at `victoria.satorre.us`).
- **Domain (confirmed by Satoy 2026-05-14):** `maning.satorre.us`
- CNAME file present and ready for GitHub Pages / Netlify deploy.

## Files

| File | Purpose |
|---|---|
| `index.html` | Full memorial — masthead, 10 sections, colophon |
| `styles.css` | Newspaper aesthetic — parchment, sepia, typewriter, cross watermark, Parian map underlay |
| `profile-notes.md` | Raw biographical notes (input source for index.html) |
| `assets/` | Photos (see manifest below) |
| `README.md` | This file |

## Photo manifest

| File | Subject |
|---|---|
| `maning-baby-portrait-1yr-4mos.jpg` | Hand-tinted studio portrait, "Manuel Satorre Jr. at the age of 1 yr & 4 mos" — earliest known photo |
| `maning-satorre-street-corner-with-son.jpg` | Cebu street corner with one of his sons (used as Front Page hero) |
| `maning-with-two-sons-porch.jpg` | Seated on a porch holding two young sons (likely 70s) |
| `maning-and-victoria-neptunes-net.jpg` | Maning and Victoria at Neptune's Net |
| `maning-golden-gate-bridge.jpg` | Golden Gate Bridge, San Francisco (vest + plaid + shoulder bag, late 70s / early 80s) |
| `maning-great-wall-china.jpg` | Great Wall of China, red-star cap + shoulder bag |

## Sections (in order)

1. **Masthead** — "Kid from Parian" nameplate, "The Cross & the Byline" subtitle
2. **Front Page** — hero photo, headline, dates, opening tribute
3. **Parian Beginnings** — early life, baby portrait, old Cebu roots
4. **The Cross** — faith, Magellan's Cross, moral grounding
5. **The Byline** — 60 years of journalism, editing, broadcasting, law
6. **The Cebu Beat** — ACJ presidency, public voice, affiliations factbox
7. **The Environmental Beat** — PEJI, AFEJ, Green Pen Award, Great Wall photo
8. **The Carolinian Legacy** — Maning AND Victoria as Outstanding Carolinians
9. **Family Edition** — husband/father/grandfather/anchor, photo strip
10. **The Archive** — articles, columns, awards factbox
11. **On the Record** — guestbook stub (CTA disabled pending backend)

## Preview locally

```bash
cd ~/.openclaw/workspace/production/maning-satorre-tribute
python3 -m http.server 8765
# then open http://localhost:8765
```

## Open questions for Satoy (asked 2026-05-13)

- **Platform** confirmation — assumed static site + Obsidian working archive.
- **Audience** — assumed unlisted at first.
- ~~**Domain** — `maning.satorre.us`? `parian.satorre.us`? Something else?~~ → **`maning.satorre.us`** (confirmed 2026-05-14)
- **Deadline / anniversary** — none stated; treating as slow-build archive.
- **Guestbook backend** — reuse Victoria's Google Apps Script + Sheets pattern? Or fresh?
- **More assets** — clippings, columns, awards photos, video? Start an intake folder?
- **Pull quote in The Cross section** is a paraphrase in his spirit, not a real Maning quote. Replace with an actual quote when one is found.

## Next steps

- [ ] Satoy review — pass / changes / additions
- [ ] Pick + register domain
- [ ] Decide on guestbook backend
- [ ] Begin clippings/columns/awards intake
- [ ] Mirror Obsidian vault page for working archive
- [ ] Deploy when ready (Netlify or GitHub Pages, same pattern as Victoria's site)
