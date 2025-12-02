# PlatinumRx_Assignment
Contents:
- SQL/: hotel & clinic schema + queries (Postgres)
- Spreadsheets/: Ticket_Analysis.xlsx (ticket + feedbacks, formulas)
- Python/: Time converter and duplicate-removal scripts

How to run:
1. SQL: load `01_*_Schema_Setup.sql` into Postgres/MySQL and run sample inserts, then run query files (02_*.sql & 04_*.sql).
2. Spreadsheets: open `Ticket_Analysis.xlsx` and verify formulas in the 'feedbacks' sheet.
3. Python: `python 01_Time_Converter.py` and `python 02_Remove_Duplicates.py`.

Assumptions:
- Timestamps are in ISO-like format (YYYY-MM-DD HH:MM:SS).
- Values in amounts are numeric.
