# Bangla Calendar

A Bengali (Bangla) calendar web app with correct Gregorian ↔ Bangla date conversion, a navigable month grid, and Bangladeshi public holidays.

Live demo: https://nafiz-xd.github.io/bangla-calendar/

## Features

- Correct Gregorian → Bangla conversion in pure JavaScript (Bangladesh standard rules: Boishakh–Bhadro 31 days, Ashwin–Choitro 30 days, Falgun 29 days / 30 in a leap year, and Agrahayan 31 days as in the official Bangladesh calendar — that extra day is what makes the year total 365/366 days and keeps 1 Boishakh on 14 April every year; also gives the well-known anchors 1 Falgun = 14 February and 1 Choitro = 15 March)
- Verified conversions: 14 April 2026 = 1 Boishakh 1433, and 20 November 2026 = 6 Agrahayan 1433
- Month grid view navigating by Bangla months, with previous / next buttons and a slide-flip transition animation
- Every cell shows the Bangla date (in Bangla numerals) plus its Gregorian date
- Today is highlighted in both calendars, with a "Go to today" shortcut
- Date converter: pick any Gregorian date and see its Bangla date instantly
- Bangladeshi fixed public holidays (21 February, 26 March, 14 April Pohela Boishakh, 1 May, 16 December, 25 December and more) marked inside the grid and listed below it
- Red-and-white design with alpona-inspired SVG border motifs and Hind Siliguri typography
- Fully responsive, no build step, no accounts or API keys — works from `file://` and on GitHub Pages

## Tech Used

- HTML5
- CSS3 (CSS grid, keyframe slide/flip animations, inline SVG patterns)
- Vanilla JavaScript (date conversion, month rendering, holiday matching)
- Google Fonts: Hind Siliguri, Playfair Display

Built by Nafiz Bin Azad
