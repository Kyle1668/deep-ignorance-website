# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is the website for the Deep Ignorance research paper hosted at deepignorance.ai. It's a static website showcasing research on filtering pretraining data to build tamper-resistant safeguards into open-weight LLMs.

## Structure

- `index.html` - Main HTML page with content about the research
- `styles.css` - CSS styling
- `images/` - Assets including logos and figures
- `deep_ignorance_paper.pdf` - The research paper
- `CNAME` - GitHub Pages custom domain configuration

## Development

This is a simple static website with no build process. Changes to HTML/CSS take effect immediately.

### Local Development
```bash
# Serve locally with Python
python3 -m http.server 8000

# Or with Node.js http-server if available
npx http-server
```

## Deployment

The site is deployed via GitHub Pages. Any commits to the main branch automatically deploy to deepignorance.ai.