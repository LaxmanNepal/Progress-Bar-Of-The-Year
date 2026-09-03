# Progress Bar of the Year

A fast, dependency-free live year-progress dashboard by **Laxman Nepal**.

## Features

- **Live year progress** — continuously calculates the percentage of the current year completed
- **Precise countdown** — days, hours, minutes and seconds remaining
- **Live / Pause controls** — freeze the dashboard whenever needed
- **Responsive glass UI** — optimized for mobile, desktop and presentation screens
- **Automatic yearly rollover** — switches to the new year without configuration
- **Dark/light appearance** — follows the device color-scheme preference
- **Reduced-motion support** — respects `prefers-reduced-motion`
- **Accessible progress bar** — semantic ARIA progress information
- **1080p cinematic export** — generate 16:9 or 9:16 WebM time-lapses directly in a supported browser
- **15 / 30 / 60 second exports** — with progress and cancellation controls
- **Share cards** — Instagram, Story, Facebook and YouTube Community sizes
- **Five share-card themes** — Green Glass, Neon Blue, Fire, Sunset and Minimal Black
- **Fullscreen mode** — useful for TVs, presentations and screen recording
- **Native sharing** — Web Share API with clipboard fallback
- **PWA support** — installable as a standalone web app on supported browsers
- **Offline support** — service worker caches the application shell and static assets
- **No framework or runtime dependency** — everything runs client-side

## Performance & privacy

- No framework
- No external JavaScript libraries
- No API calls
- No tracking code
- No backend required
- Static-hosting friendly
- Works without an account

## Deployment

Deploy the repository directly with GitHub Pages or another HTTPS static host. The core application is contained in `index.html` with PWA assets alongside it.

## PWA

The repository includes:

- `manifest.webmanifest`
- `icon-192.svg`
- `icon-512.svg`
- `sw.js`

Supported browsers can install the application and launch it in standalone mode. The service worker uses a versioned cache, refreshes navigations from the network when possible, and falls back to the cached application shell when offline.

## Browser support

The dashboard itself works in modern browsers. Cinematic video export requires browser support for `MediaRecorder` and `HTMLCanvasElement.captureStream()`. PWA installation requires HTTPS and browser support for installable web apps.
