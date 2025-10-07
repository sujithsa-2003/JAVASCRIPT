# Copilot Instructions for JAVASCRIPT Codebase

## Project Overview
This repository contains HTML files organized into two main folders:
- `CLASSWORK/`: Contains daily classwork HTML files (e.g., `day1class.html` to `day8class.html`).
- `HOMEWORK/`: Contains daily homework HTML files (e.g., `day1home.html` to `day7home.html`).

Each file typically represents a standalone HTML document for a specific day, likely used for learning or teaching JavaScript and web development concepts.

## Key Patterns & Conventions
- **File Naming:**
  - `dayNclass.html` and `dayNhome.html` where N is the day number.
  - No subfolders or grouping by topic—each day is a separate file.
- **No Build System:**
  - There are no build scripts, package managers, or external dependencies. All files are static HTML.
- **No Central Index:**
  - There is no `index.html` or navigation between files. Each file is independent.
- **No JavaScript/CSS Bundling:**
  - Any JavaScript or CSS is expected to be inline or linked directly in each HTML file.

## Developer Workflow
- **Editing:**
  - Open and edit the relevant `dayNclass.html` or `dayNhome.html` file directly.
- **Previewing:**
  - Open HTML files in a browser to view results. No special server or tooling is required.
- **Adding New Days:**
  - To add a new day, copy an existing file and increment the day number in the filename.

## Example Patterns
- To add a new classwork file for day 9:
  1. Copy `CLASSWORK/day8class.html` to `CLASSWORK/day9class.html`.
  2. Update the content as needed.
- To add a new homework file for day 8:
  1. Copy `HOMEWORK/day7home.html` to `HOMEWORK/day8home.html`.
  2. Update the content as needed.

## Recommendations for AI Agents
- When generating new files, follow the existing naming convention.
- Do not introduce build tools, frameworks, or external dependencies unless explicitly requested.
- Keep each day's file self-contained.
- Reference specific files by their full path (e.g., `CLASSWORK/day3class.html`).

## Key Files & Directories
- `CLASSWORK/` — Daily classwork HTML files
- `HOMEWORK/` — Daily homework HTML files

---
If you need to update these instructions, ensure you preserve the current structure and conventions unless the project evolves.
