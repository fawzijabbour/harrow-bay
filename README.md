# The Ledger of Harrow Bay

An SQL detective game that runs on a fake 1998-era desktop. It's November 2001, and you're a temp at the Harrow Bay Police Department records office. The last temp, Elena Voss, has vanished. Every case you solve with SQL brings you closer to finding her.

**Play it:** open `index.html` in a browser, or visit the live page on GitHub Pages.

## What it teaches

| Case | Disk | SQL |
| --- | --- | --- |
| 1. The Logged-In Machine | BASICS.DSK | SELECT, ORDER BY, LIMIT, DISTINCT |
| 2. The Badge Reader | FILTER.DSK | WHERE, AND/OR, IN, BETWEEN, LIKE, IS NULL |
| 3. The Paper Files | BUILDER.DSK | CREATE TABLE, INSERT, UPDATE, DELETE, constraints |
| 4 to 10 | coming soon | Functions, GROUP BY, design, JOINs, CTEs, window functions, indexes and transactions |

## Features

- Real SQL engine (SQLite compiled to JavaScript) running entirely in the browser
- Lessons, auto-checked practice tasks and three-step hints for every task
- Disko, a pixel floppy disk helper who explains SQL errors in plain words
- Evidence board, case notes, email inbox, messenger and a "case closed" stamp
- Progress saves automatically in the browser; a short shift code carries it to another computer
- One-click database reset
- Works offline: a single self-contained HTML file

## Tech

Vanilla HTML, CSS and JavaScript, with [sql.js](https://github.com/sql-js/sql.js) for the database engine. No build step and no server.
