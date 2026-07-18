# 🎂 Birthday Dashboard

A single page, self contained dashboard for tracking recurring birthdays no backend, no database, no sign up. Everything lives in one `index.html` file and can be hosted for free on GitHub Pages, Netlify, or Vercel.

## Features

- **Add birthdays manually** - name, month, day, and an optional note
- **Import from Excel or CSV** - upload a `.xlsx`, `.xls`, or `.csv` file with `Name` + `Month`/`Day` columns (or a single `Birthday`/`Date` column)  header matching is loose (works with "DOB," "Birth Month," etc.)
- **Auto-renews every year** - only month + day are stored, so every birthday recurs automatically with no re-entry
- **"Next Up" countdown** - a hero card always shows whoever's birthday is coming soonest
- **Full-year grid view** - all 12 months laid out as color coded tiles, current month highlighted
- **Browser notifications** - opt in to get an OS level notification when someone's birthday matches today, while the tab is open
- **Persistent storage** - data is saved automatically and reloads next time you open the page
