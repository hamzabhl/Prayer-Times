# 🕋 Prayer Times Web Page — README

A modern, responsive, Arabic-styled web application that displays Islamic prayer times, next-prayer countdown, and Hijri/Gregorian dates, with support for GPS auto-location and manual city selection (Morocco cities).

## Features  
✅ 1. Live Prayer Times :  
Fetches accurate timings from Aladhan API (https://api.aladhan.com/v1/timings)

✅ 2. Manual City Selection (Morocco) :  
Dropdown list of Moroccan cities with latitude & longitude.  
Selecting a city updates prayer times instantly.

✅ 3. Beautiful Arabic UI :  
Uses Tajawal Arabic font.  
Right-to-left (RTL) layout.  
Mosque background with glass-card effects.

✅ 4. Live Countdown Timer :  
Shows remaining time for the next prayer.  
Automatically switches to the next prayer when time arrives.

✅ 5. Hijri & Gregorian Dates :
Displays today’s Islamic date.
Arabic month names.  
Arabic weekday names.

✅ 6. Responsive Design :  
Works on all screen sizes (phones, tablets, PCs)

## Project Structure
```bash
project-folder/
│
├── index.html              # Main Web Page (HTML + JS + CSS)
├── mosque-interior.jpg     # Background image
├── package.json            # Node project metadata (axios dependency)
├── package-lock.json       # Auto-generated lockfile for npm
├── /node_modules/          # Installed dependencies (axios)
└── README.md               # Documentation
```

## Aladhan API — Prayer Timings

Used to fetch prayer times based on date & coordinates :
```bash
https://api.aladhan.com/v1/timings/{day}-{month}-{year}?latitude={lat}&longitude={lng}&method=21
```

## 🛠 Technologies Used
<table>
  <thead>
    <tr>
      <th>Technology</th>
      <th>Purpose</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>HTML5</td>
      <td>Structure of the web page</td>
    </tr>
    <tr>
      <td>CSS3</td>
      <td>Arabic UI, layout, responsive design</td>
    </tr>
    <tr>
      <td>JavaScript</td>
      <td>Countdown timer, date parsing, DOM updates</td>
    </tr>
    <tr>
      <td>Axios</td>
      <td>API requests to Aladhan</td>
    </tr>
    <tr>
      <td>Aladhan API</td>
      <td>Fetch prayer timings based on date & coordinates</td>
    </tr>
    <tr>
      <td>Google Fonts</td>
      <td>Arabic font “Tajawal” for modern UI</td>
    </tr>
  </tbody>
</table>

## Usage

```markdown
- Select a Moroccan city from the dropdown to update prayer times.  
- Check the live countdown for the next prayer.  
- Check both Hijri and Gregorian dates.
```
