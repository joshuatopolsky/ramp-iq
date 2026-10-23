# Ramp IQ

Independent prototype of a business-data console built on Ramp's published data (Ramp AI Index via FRED, Ramp research) plus a business news feed. Not affiliated with Ramp.

- `index.html` is the whole app.
- `data/series.json` holds the AI adoption series; refreshed weekly from FRED.
- `data/news.json` holds the news feed and Ramp exclusives; refreshed hourly.

Both data files are updated by scheduled Claude tasks that commit to this repo.
