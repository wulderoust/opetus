# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository

GitHub: https://github.com/wulderoust/opetus

## Git workflow

After every file change:
1. `git add <file>`
2. `git commit -m "..."` with a clean, descriptive message
3. `git push`

## Project structure

This is a collection of self-contained web games and learning projects. Each project is a single HTML file with all CSS and JS inline — no build tools, no dependencies, no server required. Open any file directly in a browser.

## Architecture

Each HTML file is fully standalone:
- **HTML** — structure
- **CSS** — inline in `<style>` in `<head>`
- **JS** — inline in `<script>` at end of `<body>`

No frameworks, no npm, no bundler. Keep it that way unless there is a compelling reason to change.
