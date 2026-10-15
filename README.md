# TriaTED – Project Website

Website for **TriaTED – Offline AI-Powered Emergency Medical Triage and Decision Support System**,
CMPE 491/492 Senior Design Project, TED University (2026–2027).

## Structure

```
index.html     the whole site (HTML + CSS in one file)
reports/       PDF reports go here
```

## Before publishing

The site already links to `reports/proposal.pdf`. Put your proposal PDF there with exactly that name.

## Adding a report

1. Upload the PDF into `reports/` (on GitHub: open the folder → Add file → Upload files), e.g. `reports/proposal.pdf`
2. In `index.html`, add one line inside `<ul class="reports" id="report-list">`:

   ```html
   <li><a href="reports/proposal.pdf" target="_blank" rel="noopener"><span>Project Proposal</span><span class="open">Open PDF</span></a></li>
   ```
3. Commit and push.
