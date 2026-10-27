# Calendar Planning

Prototype for model fittings planning. It reads an Outlook calendar (.ics export) and produces:

- **Planning message**: click any meetings in the calendar (one by one, a whole day or a whole week, across weeks) to build the WhatsApp planning. Choose which info goes in each line and in what order.
- **Tracker rows**: one row per fitting in the exact column order of the *Tracker Models DEV RTW* yearly sheet (columns A–Y). Check the blue cells, then **Copy rows for Excel** and paste in column A of the first empty row, or **Download .xlsx**. Rows are marked once copied so they are not pasted twice. Each row can also be copied on its own.

- **Year template**: a day-by-day agenda grid from 28 Sep 2026 to 31 Dec 2027 (rows J&L OOO, SS PRECO, FW PRECO, SS SHOW, FW SHOW, PAULA). Events are placed by Outlook category or by a subject prefix like `SS PRECO: Design review`; recurring series are expanded. **Export to Excel** writes `YEAR_TEMPLATE_AGENDA.xlsx` in the template layout. `sample-data/Sample_Outlook_agenda_year.ics` is an invented agenda to try it.

Opens on **invented sample fittings**. The calendar file is read in the browser and never uploaded; edits, day rates and copied marks are saved in that browser only. Single static file (`index.html`), no server.
