# Bluegrass Bloom

Bluegrass Bloom is a private, on-device money planning tool for Kentucky college students. It helps turn irregular income, recurring expenses, savings goals, shared costs, and upcoming decisions into a clearer monthly plan.

## What it does

- Guides first-time users through a short plan setup.
- Tracks paychecks, recurring expenses, one-time purchases, and housing costs.
- Shows an overview of cash flow, current balance, upcoming entries, and plan health.
- Creates savings goals with progress tracking and scheduled contributions.
- Forecasts cash flow across different time horizons and income assumptions.
- Models “what if?” decisions with saved scenarios, such as a purchase, delayed paycheck, housing change, or new contribution.
- Tracks shared expenses and lets you add your portion to the plan.
- Includes a fictional demo plan for exploring the interface.
- Exports and imports plans as JSON files for backup or moving between devices.

## Privacy

Your plan stays in the browser. Bluegrass Bloom stores plan data in `localStorage` and does not require an account or send financial information to a server. Use the export option to keep your own backup.

The built-in demo is fictional and is not financial research or a real person's data.

## Run locally

No build step or package installation is required.

1. Clone the repository:

   ```bash
   git clone https://github.com/Thestar3777/bluegrass-bloom.git
   cd bluegrass-bloom
   ```

2. Open `index.html` in a browser.

For a local web server, use any static server, for example:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deploy

The project is a static HTML application, so it can be hosted on GitHub Pages, Netlify, Vercel, or any other static hosting provider. Publish the repository root with `index.html` as the entry point.

## Project structure

```text
bluegrass-bloom/
└── index.html    # Application markup, styles, and client-side logic
```

## Important notes

- Clearing browser storage or using a different browser/device removes access to an unexported plan.
- Export a JSON backup before clearing site data or switching devices.
- Bluegrass Bloom is a planning aid, not financial, legal, or educational advice.

## License

No license has been specified yet.
