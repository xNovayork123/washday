# Washday

Booking page for a building's shared laundry room. It is built from the Week 3–4 context mapping (interviews and desk research) for GUI Design & Web Optimization.

- **Build:** https://xnovayork123.github.io/washday/
- **Lo-fi prototype:** https://xnovayork123.github.io/washday/prototype.html

## What it does

- **Wash + dry as one load.** You pick a start time and Washday finds a washer and a dryer that are free back to back. It also tells you when you'll be done.
- **Real cycle lengths.** Washers book for 1 h 30 and dryers for 2 h, on a 30-minute grid. All cycles end by 22:00 (quiet hours).
- **Next free wash + dry.** The top of the page shows the earliest full load. When a day is full, the booking form points to the next day with room.
- **My laundry.** Your bookings with a countdown, a cancel button and a calendar reminder (.ics).
- **Pickup watch.** Graduated steps for finished laundry: 15 minutes to collect, then a copyable nudge for the building chat, then the basket after 30 minutes.
- **Room rules, written down.** The unwritten rules are visible next to the schedule.

## Limitations

It's a single page (`index.html`) with no dependencies or build step. Bookings are stored in the browser's `localStorage`, so they only show up on the device where they were made. The page starts with demo bookings, and **Reset demo data** in the sidebar restores them. A real building would need a shared backend.

## Usage

Open `index.html` in a browser, or publish it with GitHub Pages (Settings → Pages → branch `main`, folder `/`).
