# Progress Bar of the Year

A fast, dependency-free live progress experience for the current year.

## What it shows

- **Year progress** — percentage of the current year completed
- **Month progress** — percentage of the current month completed
- **Day progress** — percentage of today completed
- **Live time** — hours, minutes and seconds

## Opening animation

When the page loads, every displayed value intentionally starts at **0** and animates smoothly to the real current value:

- Year percentage: `0 → actual`
- Year number: `0 → actual year`
- Month percentage: `0 → actual`
- Day percentage: `0 → actual`
- Hours: `0 → actual`
- Minutes: `0 → actual`
- Seconds: `0 → actual`

After the opening animation, the clock and progress values continue updating live.

## Performance

- No framework
- No external JavaScript
- No API calls
- No tracking
- No dependencies
- Static-hosting friendly

## Deployment

Deploy directly with GitHub Pages or any static hosting provider. The application is contained in `index.html`.

## PWA

The repository includes a web app manifest and can be installed by browsers that support installable web apps when served over HTTPS.
