# Rate Calculator

A single-page tool for tattoo artists to visualise what they actually take home under the old and new pay systems — and see exactly how much extra the boss pockets when a "cover GST" surcharge gets added.

## What it does

Enter your base rate and your cut percentage. The calculator shows you:

- **Old system** — your split of the base rate as agreed
- **New system** — what happens when you add 10% to cover the boss's GST, but your pay stays pegged to the original amount
- **The real numbers** — your actual percentage of what the customer pays drops, while the boss gains an extra 10% of your base rate per session, for free

## How to use

Just open `index.html` in any browser. No install, no dependencies, no internet required after the page loads (fonts load from Google Fonts on first visit).

## Deploying to GitHub Pages

1. Create a new repository on GitHub
2. Drop `index.html` (rename from `tattoo-rate-calculator.html`) and this `README.md` into the root
3. Go to **Settings → Pages**
4. Under **Source**, select `main` branch and `/ (root)`
5. Hit **Save** — GitHub will give you a URL to share

## Files

- `index.html` — the entire calculator, self-contained
- `README.md` — this file

## Notes

- The +10% surcharge is fixed (as that's the scenario this tool was built for), but the artist/boss split percentage is fully adjustable
- All calculations happen in the browser — nothing is sent anywhere

---

*Generated with [Claude](https://claude.ai)*
