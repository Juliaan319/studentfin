# StudentFin — Personal Finance Dashboard for Students

StudentFin is a personal finance dashboard prototype designed to help university students track spending, manage budgets, and understand their financial habits through a centralized interface.

---

## Overview

Students often know how much money they have, but struggle to understand where their money goes and whether their spending is still under control. StudentFin explores a dashboard that turns transaction data into clear summaries, spending patterns, budget awareness, and savings progress.

The prototype focuses on making common financial activities easier to review in one place: recording transactions, monitoring categories and budgets, reviewing account balances, and interpreting reports and insights.

## Key Features

- **Dashboard**
	- Total balance
	- Remaining budget
	- Monthly spending
	- Financial insight
- **Transactions**
	- Add transactions
	- Edit and delete transactions
	- Categories and tags
	- Search and filtering
- **Budget**
	- Category budgets
	- Spending progress
	- Budget monitoring
- **Insight & Analytics**
	- Spending breakdown
	- Income versus expense trend
	- Data-driven financial insights
	- Weekday and weekend spending context
- **Reports**
	- Current-period financial summary
	- Category breakdown
	- Cash-flow summary
	- Historical demo reports
- **Savings Goals**
	- Progress tracking
	- Target amounts
	- Remaining amounts
	- Projected completion
- **Accounts**
	- Multiple account types
	- Balance overview
	- Account distribution
	- Simulated synchronization
- Dark and light mode
- Responsive layout

## UX / Design Focus

The interface focuses on information hierarchy and fast scanning rather than presenting every metric with equal emphasis. Key design priorities include quick transaction entry, clear financial summaries, actionable spending insights, readable data visualization, budget awareness, savings progress, and a responsive experience across screen sizes.

## Research & Usability Testing

The project was evaluated with 20 mahasiswa kos using 5 task scenarios.

| Measure | Result |
| --- | ---: |
| Overall SEQ | 4.48 / 5 |
| SUS | 87.65 / 100 |
| SUS interpretation | Excellent |

| Task | Score |
| --- | ---: |
| Integrasi Akun | 4.40 |
| Pencatatan Tunai | 4.40 |
| Tag | 4.50 |
| Budget | 4.45 |
| Report Charts | 4.65 |

## Tech Stack

- HTML
- CSS
- JavaScript
- Chart.js 4.4.1, loaded through jsDelivr

The prototype runs in the browser and does not use React, TypeScript, Tailwind, a backend framework, a database, or a bank API.

## Prototype Limitations

These limitations reflect the current prototype scope and identify areas for future development:

- Bank and e-wallet synchronization is simulated.
- There is no real bank API integration.
- Historical reports use demo data.
- PDF export is not implemented.
- Financial insights use data-driven rules and calculations, not a real AI model.
- Some account and target-management actions are represented as prototype interactions rather than complete production workflows.

## My Contribution

My contribution focused on product/design development and project implementation, including:

- Contributing ideas to the product concept
- Helping define the interaction and data structure
- Implementing and refining interface functionality
- Working on data visualization and financial calculations
- Testing the application
- Preparing presentation materials
- Presenting the project

## Screenshots

Selected interface screenshots will be added here.

## Project Structure

- `index.html` — Application structure, page markup, styles, and UI components
- `app.js` — Application logic, state, calculations, charts, and interactions
- `README.md` — Project documentation

## Getting Started

StudentFin is a static HTML/CSS/JavaScript prototype. To run it locally, open `index.html` in a modern browser.

For a local development server, use any static file server and serve the project directory. No package installation or build step is required.

## Live Demo

Live demo: to be added

## Portfolio Case Study

Detailed case study covering the problem, design decisions, usability testing, and final product will be available in my portfolio.
