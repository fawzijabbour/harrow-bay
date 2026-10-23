# The Ledger of Harrow Bay

An SQL detective game that runs on a fake 1998-era desktop. It's November 2001, and you're a temp at the Harrow Bay Police Department records office. The last temp, Elena Voss, has vanished. Every case you solve with SQL brings you closer to finding her.

**Play it:** open `index.html` in a browser, or visit the live page on GitHub Pages.

## What it teaches

| Case | Disk | SQL |
| --- | --- | --- |
| 1. The Logged-In Machine | BASICS.DSK | SELECT, ORDER BY, LIMIT, DISTINCT |
| 2. The Badge Reader | FILTER.DSK | WHERE, AND/OR, IN, BETWEEN, LIKE, IS NULL |
| 3. The Paper Files | BUILDER.DSK | CREATE TABLE, INSERT, UPDATE, DELETE, constraints |
| 4. Mainframe Garbage | DECODER.DSK | UPPER, TRIM, SUBSTR, CASE WHEN, COALESCE, CAST, ROUND |
| 5. The Invoices | LEDGER.DSK | COUNT, SUM, AVG, MIN, MAX, GROUP BY, HAVING |
| 6. The Missing Diagram | ARCHITECT.DSK | Normalization, primary and foreign keys, INSERT ... SELECT |
| 7. The Org Chart | NETWORK.DSK | JOIN, LEFT JOIN, self joins, UNION, EXCEPT |
| 8. Companies Inside Companies | DEEPDIVE.DSK | Subqueries, IN, EXISTS, WITH, WITH RECURSIVE |
| 9. The Server Logs | TIMELINE.DSK | ROW_NUMBER, PARTITION BY, LAG, LEAD, running totals |
| 10. Format C: | MASTERKEY.DSK | Indexes, EXPLAIN QUERY PLAN, views, transactions, triggers |

All ten cases are playable, and solving Case 10 unlocks the ending.

## Features

- Real SQL engine (SQLite compiled to JavaScript) running entirely in the browser
- Lessons, auto-checked practice tasks and three-step hints for every task
- Disko, a pixel floppy disk helper who explains SQL errors in plain words
- Windows you can drag, resize from any edge or corner, and maximise (double-click the title bar)
- Evidence board, case notes, email inbox, messenger and a "case closed" stamp
- Story documents that unlock as you go: memos, faxes, a restored database diagram, a tape note and the final Gazette front page
- Mouse-click sounds on every button and icon, and deep mechanical keyboard sounds while typing queries
- Harbour FM: an original lo-fi soundtrack (rain, vinyl crackle, foghorn) composed in code and generated live, with a radio in the taskbar that turns it down 10% per click
- Progress saves automatically in the browser; a short shift code carries it to another computer
- One-click database reset
- Works offline: a single self-contained HTML file

## Tech

Vanilla HTML, CSS and JavaScript, with [sql.js](https://github.com/sql-js/sql.js) for the database engine. No build step, no server, no external requests.

## Privacy

The game makes no outside connections: the SQL engine and fonts are built into `index.html`, and a Content Security Policy blocks all network requests. Progress is saved only in the player's own browser. No cookies, analytics or tracking.

## License

Code and story: MIT License, see [`LICENSE`](LICENSE). Bundled sql.js and fonts keep their own licenses, see [`THIRD-PARTY-NOTICES.md`](THIRD-PARTY-NOTICES.md).
