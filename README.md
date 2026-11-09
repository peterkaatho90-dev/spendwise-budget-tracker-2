# SpendWise

A simple personal expense tracker built with HTML, CSS and vanilla JavaScript. Data is stored in the browser using `localStorage`.

**Live site:** https://YOUR-SITE-NAME.netlify.app  <!-- replace after deploying -->

## Features
- Dashboard with total income, expenses and balance
- Spending breakdown by category
- Add, search, filter and delete transactions
- Responsive layout, no build step required

## Project structure
```
spendwise/
├── index.html          # Dashboard
├── transactions.html   # Add / filter transactions
├── about.html          # About page
├── 404.html            # Custom not-found page (used by Netlify)
├── css/style.css
├── js/app.js
└── images/favicon.svg
```

## Run locally
Open `index.html` in your browser, or serve the folder:
```
python3 -m http.server 8000
```

## Deployment
Hosted on Netlify, connected to this GitHub repository. No build command; publish directory is the repository root. Every push to `main` triggers an automatic deploy.
