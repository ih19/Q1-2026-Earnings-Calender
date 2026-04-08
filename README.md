# Q1 2026 Earnings Calendar

An interactive earnings calendar tracking the biggest public companies reporting this quarter — built with vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies, fully self-contained.

## Live Demo

[View the live site](https://ih19.github.io/Q1-2026-Earnings-Calender/)

## Features

- **10 companies tracked** — Netflix, Tesla, Amazon, Alphabet, Meta, Apple, Microsoft, JPMorgan, Visa, NVIDIA
- **Live countdown timers** to each earnings date
- **Consensus estimates** — EPS, revenue, forward P/E, and last quarter's EPS surprise for each company
- **Expandable "What to Watch" cards** — analyst-sourced catalysts and risks specific to each company
- **Filters** — by month (April / May), status (Upcoming / Reported), and live search
- **Dark theme** — clean, professional design
- **Mobile responsive**

## Data Included Per Company

| Field | Description |
|---|---|
| Earnings Date | Confirmed or consensus-estimated report date |
| EPS Estimate | Wall Street consensus EPS |
| Revenue Estimate | Consensus revenue forecast |
| Forward P/E | Based on FY2026 estimates |
| Last Quarter Surprise | Actual EPS vs estimate, % beat/miss |
| What to Watch | Key catalysts and risks analysts are focused on |

## Companies Covered

| Company | Ticker | Report Date |
|---|---|---|
| JPMorgan Chase | JPM | Apr 14, 2026 |
| Netflix | NFLX | Apr 16, 2026 |
| Tesla | TSLA | Apr 22, 2026 |
| Visa | V | Apr 22, 2026 |
| Amazon | AMZN | Apr 23, 2026 |
| Alphabet | GOOGL | Apr 28, 2026 |
| Meta Platforms | META | Apr 29, 2026 |
| Apple | AAPL | Apr 30, 2026 |
| Microsoft | MSFT | Apr 30, 2026 |
| NVIDIA | NVDA | May 28, 2026 |

## Tech Stack

- HTML5
- CSS3 (custom properties, grid, flexbox)
- Vanilla JavaScript (no libraries)

## Usage

Clone the repo and open `index.html` in any browser — no build step or server required.

```bash
git clone https://github.com/ih19/Q1-2026-Earnings-Calender.git
cd Q1-2026-Earnings-Calender
open index.html
```

## Deployment

Hosted via GitHub Pages. To deploy your own fork:

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://ih19.github.io/Q1-2026-Earnings-Calender/`

## Data Sources

Estimates sourced from analyst consensus (FactSet, Visible Alpha, TradingView, Benzinga) as of April 2026. For informational purposes only — not investment advice.

## Author

**Ihor Holubets** 
