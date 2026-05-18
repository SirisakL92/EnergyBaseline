# Energy Baseline — Multi-Month Analyzer

Interactive web tool for **ISO 50001 / EnMS** Energy Baseline analysis.

## Features

- Import Excel files (`.xlsx`, `.xls`, `.csv`) — supports multiple files
- Auto-detect F-RCMDS-C-015 format with Thai date (Buddhist Era) conversion
- Auto-split data by month with range selection
- **Simple Linear Regression** (Y = mx + b) per variable
- **Multiple Linear Regression** (Y = b0 + b1X1 + b2X2 + ...)
- Statistical metrics: R², Adjusted R², CV(RMSE), F-statistic, P-Value
- IPMVP criteria validation (R² ≥ 75%, CV ≤ 25%)
- Scatter plots, residual plots, CUSUM chart
- Monthly comparison and trend analysis
- Export results to Excel

## Usage

### GitHub Pages

Visit: `https://<username>.github.io/<repo-name>/`

### Local

Open `index.html` in Chrome or Edge (requires internet for CDN libraries).

## Setup GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Source: **Deploy from a branch**
4. Branch: `main` / `root`
5. Save — your site will be live

## Tech Stack

- **SheetJS** (xlsx.js) — Excel file reading
- **Chart.js** — Data visualization
- Pure JavaScript — No build tools required

## Variables

| Axis | Column | Description |
|------|--------|-------------|
| Y | G (Actual) | Energy consumption (kWh) |
| X1 | L (Batch) | Production batch count |
| X2 | M (Time) | Production time (min) |
| X3 | N (Thickness) | Product thickness (mm) |
| X4 | O (Weight Input) | Input weight (kg) |
| X5 | P (Width) | Product width (mm) |

## License

MIT
