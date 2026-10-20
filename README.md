# Fittings Planner

Prototype for model fittings planning, built around the RTW model tracker's columns (A–Y of the yearly sheet).

- **Planning message**: the WhatsApp planning in `name > time > purpose > location > team` format.
- **Tracker rows**: fittings from the calendar that are not in the tracker yet. Check them, then **Copy rows for Excel** (paste in column A of the first empty row) or **Download .xlsx**. Each row can also be copied on its own.
- **Budget**: year budget, Estimé vs Réel by month and by agency.
- **Invoices**: fittings waiting for an invoice reference, and totals per reference.

Opens on **invented sample data**. "Load .ics" reads an Outlook calendar export and "Load tracker" reads the tracker .xlsx. Both are read in the browser and never uploaded. Single static file (`index.html`), no server.
