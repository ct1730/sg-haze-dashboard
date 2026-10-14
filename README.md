# SG Haze Dashboard 🇸🇬

Real-time Singapore air quality & PSI visualization dashboard. Dark-themed, responsive, zero-dependency single-page web app.

## Features

- **Live PSI readings** for all 5 Singapore regions (North, South, East, West, Central)
- **Island-wide average PSI gauge** with color-coded health status
- **Interactive region map** with PSI bubbles
- **Pollutant breakdown** (PM2.5, PM10, SO2, NO2, O3, CO)
- **24-hour PSI trend chart**
- **Auto-generated health advisory** based on current PSI
- **Auto-refresh** every 5 minutes
- **Fully responsive** — works on desktop and mobile

## Data Source

[NEA Singapore](https://www.nea.gov.sg/) via [data.gov.sg](https://data.gov.sg/) API (official, updated hourly)

## Tech

Single `index.html` — no build step, no dependencies. All CSS inline, vanilla JS, fetch API.

## Local Dev

```bash
python -m http.server 8000
# open http://localhost:8000
```

## License

MIT
