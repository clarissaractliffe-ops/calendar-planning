# Fittings Planner

Prototype for model fittings planning. It reads Marie's Outlook calendar (.ics export) and produces:

- **Planning message**: the WhatsApp planning in `name > time > purpose > location > team` format.
- **Tracker rows**: one row per fitting in the exact column order of the *Tracker Models DEV RTW* yearly sheet (columns A–Y). Check the blue cells, then **Copy rows for Excel** and paste in column A of the first empty row, or **Download .xlsx**. Rows are marked once copied so they are not pasted twice. Each row can also be copied on its own.

Opens on **invented sample fittings**. The calendar file is read in the browser and never uploaded; edits, day rates and copied marks are saved in that browser only. Single static file (`index.html`), no server.
