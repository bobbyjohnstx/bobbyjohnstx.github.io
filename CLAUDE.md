# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal GitHub Pages site for Bobby Johns (bobbyjohnstx.github.io). Single-page static site — one `index.html` file with inline CSS, no build step, no JavaScript, no frameworks.

## Development

Open `index.html` directly in a browser to preview. No server required. To deploy, push to `main` — GitHub Pages serves automatically.

## Design System

Uses the **official Red Hat color palette and typography** from the Red Hat Brand Messaging & Standards Guide (v1.3). Reference: `/Users/bjohns/Documents/bjohns_offline_repo/5_work_projects/redhat_branding/Red_Hat_Brand_Messaging_Standards_Guide.txt`

**Colors:** CSS variables follow Red Hat naming (`--red-50`, `--gray-80`, `--purple-70`, etc.). Primary brand color is `--red-50: #ee0000`. Red is used sparingly — currently only the signature hero line and the GitHub button.

**Fonts:** Red Hat Display (headlines), Red Hat Text (body), Red Hat Mono (code/labels) — loaded from Google Fonts. Fallbacks: Arial Black, Arial, Consolas.

**Design philosophy:** Restraint-first. Left-aligned hero, list-based layouts (not cards), alternating section backgrounds (black → gray-80 → black → purple-70) for rhythm. The tinycode section is the one "bold moment" breaking from the minimal palette.

## Content Sources

- **GitHub repos:** Fetched via `gh repo list bobbyjohnstx --visibility=public --json name,description,url,stargazerCount,primaryLanguage`
- **Medium articles:** Profile at `https://medium.com/@bjohns_49809`
- **LinkedIn:** `https://www.linkedin.com/in/bobbyjohns/` — 25+ years in tech, Red Hat, Dallas TX
