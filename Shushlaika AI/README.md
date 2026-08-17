# Shushlaika AI

**Upload a spreadsheet. Talk to it.**

![Shushlaika AI workspace — spreadsheet view with an AI chat panel](screenshots/workspace.png)

## What it is

Shushlaika AI is a data workspace built around one idea: you shouldn't need to write a formula, open a notebook, or remember pandas syntax to clean up or understand a spreadsheet. Upload a CSV, and you get a real spreadsheet view on one side and an AI assistant on the other — ask it questions about your data, or tell it what to fix, in plain language.

## What you can do with it

- **Ask questions about your data** — "how many duplicates are there", "what's odd about this column" — and get an answer grounded in what's actually in the file, not a generic guess.
- **Clean it up in one click** — one-tap actions for the things you do on every messy dataset: find outliers, remove duplicates, spot empty values, pull summary statistics.
- **Ask for anything more specific in plain language** — when a request doesn't match a built-in action, the assistant works out the right transformation itself instead of shrugging.
- **Never lose the original** — every change becomes a new version (Original → v1 → v2 →…) instead of overwriting your file, so you can always see exactly what changed and step back if it's wrong.
- **See it update live** — the workspace reflects new files and changes in real time, no manual refresh.
- **Export whenever you're done** — take the cleaned result back out as a CSV.

## What makes it hold up

- **It picks its own method, you don't.** For a request it already knows how to do well — dedupe, outliers, nulls, stats — it answers instantly with a proven routine. For anything more specific, it reasons about your actual data and works out the transformation itself. For a plain question, it just answers — no unnecessary edits to your file. You never have to know which of these you need; you just ask.
- **It reads your data before it answers.** Before touching anything, the assistant builds a real profile of the file in front of it — column types, missing values, how many distinct values live in each column — so its answers and its edits are grounded in what your data actually looks like, not what a "typical CSV" usually looks like.
- **Nothing is destructive.** Every action — yours or the AI's — is recorded as a new version with what was asked and what changed, not a silent overwrite. Your original upload is always one click away.
- **It's a real workspace, not a one-shot script.** Files, versions, and history are tied to your account and stay there — this is a place you come back to and keep working in, not a single-use tool you run once and lose the result.

---

*This is a product showcase. Shushlaika AI's implementation is not included in this repository.*
