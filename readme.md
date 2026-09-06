#  Convert Excel table to ical 

Takes an excel table containing names with a rota and links this to a time.
E.g. a reoccuring committee or gathering can be linked.
Names have been made anonimous and adress removed.
Assumes same time and place, you can adjust that by putting more info in the table for example.
Not full user friendly but saves you from learning how the ics package works.

## Static page

A user friendly version runs in the browser: **https://daafip.github.io/excel-table-to-ical/**

It is a single file, [`index.html`](index.html) — no build step, no server. Paste a table (or drop
an `.xlsx`/`.csv`), set the time and place, download the `.ics`. To run it locally, just open the
file in a browser.

Every push to `main` that touches `index.html` redeploys the page via
[`.github/workflows/pages.yml`](.github/workflows/pages.yml).
