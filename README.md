# ScrapVenture — SQA Testing Challenge Build

A React + Vite web app (ScrapVenture recycling site and marketplace) prepared for manual software-quality-assurance practice.
This build contains intentionally placed functional defects of varying severity across the site. Your task is to explore it, find them, and write clear defect reports.

## Run
```bash
npm install
npm run dev        # development
npm run build      # production build -> dist/
npm run preview    # serve the production build
```

## Pages to test
Home, Marketplace (catalog, filters, cart, checkout, order tracking), Book a Pickup (5-step wizard + tracking), Become a Collector, Our Team, Awards.

## Notes for testers
- Test on desktop and phone-sized viewports, with mouse and keyboard.
- Data is stored in browser `localStorage`; clear it to reset the demo state.
- Report each defect with steps, expected vs actual result, and severity.
