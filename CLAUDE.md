# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is the website for the Deep Ignorance research paper hosted at deepignorance.ai. It's a static website showcasing research on filtering pretraining data to build tamper-resistant safeguards into open-weight LLMs.

## Key Files

- `index.html` - Main page with research content, author information, artifacts table, and press coverage
- `styles.css` - CSS styling with responsive design and print styles
- `deep_ignorance_paper.pdf` - The research paper (arXiv:2508.06601)
- `images/` - Logos (EleutherAI, Oxford, WaPo, HF) and research figures
- `CNAME` - GitHub Pages custom domain (deepignorance.ai)

## Content Structure

The website presents:
1. Paper abstract and key findings
2. Visual results showing model performance vs tamper resistance
3. Released model artifacts table (15+ model variants with different filtering strategies)
4. Press coverage section with linked articles
5. Citation information in BibTeX format

## Development

Static website with no build process. Changes to HTML/CSS take effect immediately.

### Local Development
```bash
# Serve locally with Python
python3 -m http.server 8000

# Or with Node.js http-server if available
npx http-server
```

### Testing Responsiveness
The site uses responsive CSS breakpoints at 768px and 480px. Test at various viewport sizes.

## Deployment

GitHub Pages deployment from main branch. Commits to main automatically deploy to deepignorance.ai.

## Style Guidelines

- Primary color: `#154d39` (deep green) used for headings and emphasis
- Font: Poppins for headings, system fonts for body text
- All external links open in new tabs (`target="_blank"`)
- Images use descriptive alt text for accessibility
- Tables use semantic HTML with proper header structure