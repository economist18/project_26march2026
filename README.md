# project-26march2026

## Project Structure

```
project_26march2026/
├── CLAUDE.md              # Research rules & estimation philosophy (permanent)
├── README.md              # This file — project-specific notes
├── code/
│   ├── R/                 # R scripts
│   ├── python/            # Python scripts
│   └── stata/             # Stata do-files
├── data/
│   ├── raw/               # Original source data (never modify these)
│   └── clean/             # Cleaned and merged datasets
├── output/
│   ├── tables/            # Generated tables (LaTeX, CSV)
│   └── figures/           # Generated figures (PDF, PNG)
├── documents/             # Outside papers and PDFs (split with /split-pdf)
├── decks/                 # Beamer presentations (rhetoric of decks philosophy)
├── notes/                 # Scratch notes, ideas, miscellaneous
└── progress_logs/         # Session logs for continuity across Claude conversations
```

## How This Project Is Organized

**Two configuration files serve different purposes:**
- `CLAUDE.md` contains permanent research rules — estimation philosophy, coding conventions, and instructions that apply across all sessions. It is copied from a master template at `~/mixtapetools/claude/CLAUDE.md` and edited as the project evolves.
- `README.md` (this file) is project-specific documentation — what the project is about, who's involved, current status, and key decisions.

**Session continuity:** The `progress_logs/` directory maintains a running record of work across Claude Code sessions. If a session is lost or a new conversation starts, the latest log provides context to resume seamlessly.

**Documents and decks:** Outside papers go in `documents/` and can be split for safe reading using the `/split-pdf` skill. Presentations are built in `decks/` following the rhetoric of decks philosophy from `~/mixtapetools/presentations/rhetoric_of_decks.md`.

## Overview

[To be filled in]

## Collaborators

- Scott Cunningham

## Status

Phase: Setup

## Key Files

| Purpose | Location |
|---------|----------|
| Analysis code | `code/` |
| Source data | `data/raw/` |
| Results | `output/` |
| Presentations | `decks/` |
