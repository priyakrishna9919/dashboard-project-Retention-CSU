# CSU Analytics Portal — Cleveland State University

A unified executive analytics portal hosting all CSU institutional dashboards in one place. Built on publicly available data. No backend, no login — works in any browser.

## Live URL
**https://priyakrishna9919.github.io/dashboard-project-Retention-CSU/**

## Dashboards

| Dashboard | Status | Description |
|-----------|--------|-------------|
| [Enrollment Executive](dashboards/enrollment.html) | ✅ Live | Total enrollment, UG/Grad mix, FT/PT, 10-yr trend |
| [Retention & Student Success](dashboards/retention.html) | ✅ Live | Retention rates, grad rates, equity gaps, peer benchmarks |
| Geographic Analysis | 🔨 Coming Soon | US map, Ohio county map, OOS feeder states |
| Enrollment Pipeline | 🔨 Coming Soon | Funnel, new entrants, transfer trends |
| Financial Aid | 📋 Planned | Pell rates, net price, aid gaps |
| Academic Outcomes | 📋 Planned | Degrees awarded, time-to-degree |

## Data Sources
- IPEDS (Enrollment, Retention, Completions, Financial Aid surveys)
- CSU At-a-Glance
- CSU Common Data Set (CDS)
- CSU Book of Trends
- Ohio Department of Higher Education
- CSU President's Report
- College Scorecard

## Features
- 4 live filters per dashboard (Year, College, Level, Status)
- Active filter pills with one-click clearing
- All charts update in real time — no page reloads
- CSU green & gold brand system throughout
- Mobile responsive
- No backend, no auth, no build tools needed

## Local Development
```bash
git clone https://github.com/priyakrishna9919/dashboard-project-Retention-CSU.git
cd dashboard-project-Retention-CSU
# Open index.html in browser, OR:
npx serve .
```

## Enable GitHub Pages
Settings → Pages → Branch: main → / (root) → Save  
Live at: `https://priyakrishna9919.github.io/dashboard-project-Retention-CSU/`
