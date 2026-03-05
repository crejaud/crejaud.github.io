# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Static personal portfolio website for Corentin Rejaud, hosted via GitHub Pages at www.corentinrejaud.com. No build system, no frameworks, no package manager — just plain HTML and CSS.

## Architecture

- `index.html` — Single-page site with anchor-based navigation (About Me, Education, Skills, Experience, Projects, Courses, Contact)
- `main.css` — All custom styles; uses Bootstrap grid (col-md-*) loaded from external CDN
- `images/` — Static assets (logos, backgrounds)
- `CNAME` — Custom domain config for GitHub Pages

## Development

Open `index.html` directly in a browser to preview. No build or serve step required. External dependencies (Bootstrap CSS, Shift font) are loaded via CDN links in the HTML head.

## Conventions

- Layout uses Bootstrap 3 grid system (`col-md-*`, `container`, `row`)
- Section headers use `.scroll` divs with background images as visual separators
- Color scheme: nav `#475F77`, hero/accent `#D74B4B`, content sections `#DCDDD8`
- The `'Shift'` font family is used throughout for headings

## Git

- Do NOT add a `Co-Authored-By` line to commits
