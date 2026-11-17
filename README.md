# Pulse Lab V2 — Preview

Independent mobile-first preview of Pulse Lab. Original repository remains unchanged.

## Included in this deployed preview
- HRmax comparison: Fox, Tanaka, Nes, and measured HRmax override
- Example %HRmax / %HRR training zones
- HR Recovery (60s)
- Simple Heart Rate Drift
- Basic RMSSD from manually entered NN intervals
- Local athlete profiles and session log
- JSON backup and restore; browser print-to-PDF

## Important limitations
This is a **small static preview**, not yet the full React + TypeScript application and not a complete migration of the old repository. No BLE, validated CSV importer, full HRV artifact processing, TRIMP, advanced threshold zones, or offline service worker yet. Local storage is not encrypted and may be lost if browser data is cleared. Do not enter sensitive athlete data on shared devices.

## Hosting
GitHub Pages via Actions. In repository Settings > Pages choose **GitHub Actions** as source.

## Original
https://github.com/mk0007160-maker/pulse-lab-heart-rate
