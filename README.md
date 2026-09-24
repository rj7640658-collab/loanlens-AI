# FinSight AI — AI Loan Eligibility Checker Prototype

A self-contained academic prototype based on the supplied project brief.

## Run
1. Open the repository and launch index.html in Chrome/Edge, or use VS Code + Live Server.
2. No build command is required.

## Included
- Loan Eligibility Checker
- Credit Score Analyzer
- EMI Calculator
- AI Financial Tips demo chat
- Responsive mobile/desktop UI
- Dark glassmorphism design
- Form validation and transparent demo scoring
- Project workflow section

## Important prototype notes
The AI chat is a local demo response generator. It does NOT call Claude from the browser.
For a real implementation, put the Claude API key on a backend/serverless function and call that backend from the frontend. Never expose an API key in app.js.

Google Sheets integration is intentionally not wired into the frontend prototype. For production, use a backend or Google Apps Script endpoint with authentication and appropriate data-minimization/security controls.

The eligibility score is an educational demo and must not be represented as an actual bank/credit decision.