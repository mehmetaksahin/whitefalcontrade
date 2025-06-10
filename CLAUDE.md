# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML website for White Falcon Trade, a cryptocurrency education platform. The site is hosted on GitHub Pages with a custom domain (whitefalcontrade.com).

## Architecture

- **Single-page static site**: The entire website is contained in `index.html`
- **No build process**: Pure HTML/CSS with inline styles, no JavaScript frameworks or build tools
- **GitHub Pages deployment**: Uses CNAME file for custom domain configuration
- **External dependencies**: Only Google Fonts (Roboto) loaded via CDN

## Development

Since this is a static HTML site, no build, test, or lint commands are needed. Changes can be made directly to `index.html` and will be reflected immediately when deployed.

## Deployment

The site is automatically deployed via GitHub Pages when changes are pushed to the main branch. The CNAME file configures the custom domain.