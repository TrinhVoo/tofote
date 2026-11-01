# tofote

**tofote** (tofu + note) is a bilingual (English / Vietnamese) diary for tracking food allergens, histamine triggers and skin flares. It is a single static page with no server, no account and no tracking.

**Live demo:**
<img width="1861" height="886" alt="image" src="https://github.com/user-attachments/assets/cf0540d0-9e1d-43af-9ff5-ff81f0d770c8" />
<img width="1857" height="889" alt="image" src="https://github.com/user-attachments/assets/91707980-7e45-4525-ba04-4b8661c1b6d8" />
<img width="1861" height="882" alt="image" src="https://github.com/user-attachments/assets/269b4c3a-d213-4885-84e2-f78d2be74a87" />

## Features

* **Trigger checker:** search about 90 foods, ingredients and skin irritants in English or Vietnamese (accents optional) and see a status for each: 🔴 severe, 🟡 high histamine or moderate, 🔵 untested or needs caution, 🟢 safe.
* **Food and cosmetics scanner:** paste a recipe, a meal description or a cosmetic ingredient list. Every match is highlighted and cross-checked against your list.
* **Daily log:** record meals, a 1–5 skin rating, a 1–5 stress rating and notes. Meals can be picked from your recipe library, and a warning appears when a meal contains something on your list.
* **Skin calendar:** each day is coloured green to red by the worst skin rating logged that day, with a monthly average, flare-day count and trend chart.
* **Recipe library:** low-histamine vegetarian starters (Vietnamese and other cuisines), your own recipes (add, edit, delete) and colour-chip filters that hide recipes containing your triggers.
* **Your own list:** add, edit and re-rate triggers, and create your own categories.
* **Backup:** export and import all data as JSON.
* **Responsive:** a collapsing icon sidebar on desktop and a bottom tab bar on phones.

## Tech

HTML, [Tailwind CSS](https://tailwindcss.com) (CDN) and vanilla JavaScript in one file. Data is kept in the browser's `localStorage`. Typeface: DM Sans.

## Run it

Download `index.html` and open it in a browser. An internet connection is needed for the Tailwind and font files.

## Privacy

Everything stays in your own browser. Nothing is sent anywhere. Export a backup if you want to move your data to another device.

## Disclaimer

The starter lists are a general guide compiled from public low-histamine, mast-cell and contact-dermatitis resources, and are editable. They are not medical advice. Check anything important with your doctor.

