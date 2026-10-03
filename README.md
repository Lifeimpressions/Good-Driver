# Good Driver
### Road safety for everyone

A mobile-friendly web app for road safety awareness, built for the Appathon.

## Features
- **Good Driver test (driving game)** – drive past 10 road signs and react correctly (stop, slow down, keep left, don't overtake, no horn…). Score 10/10 to pass; otherwise drive again. Passing unlocks a **Good Driver badge sticker** with a QR code that opens the test (`index.html#game`), so other drivers who scan it can earn their own badge.
- **Traffic sign learning** – 22 Indian road signs (mandatory, cautionary, informatory) with progress tracking
- **Road safety quiz** – 10 random questions per round with instant explanations and best-score tracking
- **Safe ride check** – pre-ride checklist for two-wheelers and cars, plus a break reminder timer
- **Helmet & seatbelt awareness** – facts (WHO, MoRTH), Motor Vehicles Act fines, myths vs facts
- **EV dashboard mode (journey lock)** – for long trips, the vehicle stays in 20 km/h limited mode until sensor checks (seatbelt/helmet, tyre pressure, battery vs route, brakes, driver alertness) and driver confirmations are complete. Includes an emergency override that is logged. Open with `index.html#dashboard`.
- **Emergency SOS** – press-and-hold SOS with GPS location message, emergency numbers (112, 108, 100, 101, 1033), saved contacts and golden-hour first aid

## Tech
Single-file HTML, CSS and JavaScript. No install or build step. Data is saved in the browser (localStorage). Works on phones and laptops, in light and dark mode.

## Run it
Open `index.html` in any browser, or visit the live site on GitHub Pages.
