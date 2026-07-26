# Ahbab Health Education Institute — Feasibility Builder

An interactive, step-by-step financial feasibility dashboard for the Ahbab Health Education
Institute (Islamabad). Built from the project's financial feasibility study and the
Sarhad University Fee Structure 2025-26.

**Live:** https://ahbab-feasibility-dashboard.vercel.app
(auto-deploys from `main` on every push)

## What it does

A single, self-contained HTML file (no build, no dependencies, works offline). A 7-step wizard:

1. **Investment** — amount, projection horizon, tax rate
2. **Programmes** — tick any of the 21 Sarhad programmes in/out; fees pull automatically
3. **Enrolment** — new students per programme, per year (programmes can start in later years)
4. **Scholarships** — male / female discount and coverage, per programme, per year
5. **Costs** — a staffing roster (role × monthly salary × headcount per year) plus an
   add/remove list of any other cost line
6. **Scenarios** — the best / worst income and cost swing
7. **Results** — Best / Expected / Worst feasibility: profit, ROI, IRR, payback, full P&L, charts

## Running locally

Just open `Ahbab-Feasibility-Dashboard.html` in any browser. No server required.

## Notes

The revenue engine reproduces the source study's student counts and gross fees to the rupee.
A planning model — not a substitute for professional accounting or legal advice.
All amounts in PKR.
