# Kulhudhuffushi Flight Hub

A 3D planning board by GarudX for the UPU LIFT pilot (RFP-2026-009). It shows drone mail delivery from the Kulhudhuffushi hub to five Maldives Post offices: Nolhivaranfaru, Goidhoo, Hoarafushi, Makunudhoo and Funadhoo.

Open `index.html` in a browser, or turn on GitHub Pages for this repo.

## What it shows

- A live 3D route simulation with deck.gl over real OpenStreetMap island and reef outlines. You can compare the three-loop plan with the hub-and-spoke plan, and an electric aircraft with a hybrid one.
- Wind flow for the selected month, plus columns showing how many hours gust over 13 m/s at each post office.
- Airport runways from OpenStreetMap, with approach surfaces drawn to ICAO Annex 14 proportions and 5 km buffers. These are for planning only.
- Heatmaps of wind, gusts and rain by month and hour (2021–2025), monthly wind roses, and flyable hours by site.
- The route's range against the tender's 80 km spec, the plan for one delivery day, the CHF 50,000 budget and the cash position.

## Data sources

- Weather: Open-Meteo historical reanalysis (based on ERA5), hourly from 2021 to 2025, at each post-office coordinate.
- Islands, reefs and runways: © OpenStreetMap contributors (ODbL).
- Route coordinates, ground conditions, flight frequency and payment terms: UPU RFP-2026-009, Annex 1 and the Q&A.
- Costs, cruise speeds and battery figures are planning assumptions.

© GarudX Multipurpose Pvt. Ltd., 2026
