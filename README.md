# Agentic Uncertainty Atlas

An interactive companion to *Uncertainty in LLM Agents: A Comprehensive Survey*.

**Website:** https://shiiiikw.github.io/agentic-uncertainty-atlas/

The atlas covers motivation, definitions, quantification, calibration, utilization, four application domains, and nine open research questions. It includes all 245 reference records, direct paper links, a method comparison, and the original PDF with clickable citations.

## Updating the website

GitHub Pages publishes the repository root from the `main` branch. Push changes to `main` to update the public website. No build step or API keys are required. `.nojekyll` preserves the static files as authored.

## Local preview

Run `python3 -m http.server 4173` from this directory and open http://localhost:4173/.

## Content

- `index.html`, `styles.css`, `atlas.css`: page shell and styling.
- `app.js`, `guide.js`, `experience.js`, `atlas.js`: browsing, search, classification, and the PDF reader.
- `data.js`, `sections.js`: bibliography, taxonomy, and section citations.
- `assets/survey.pdf`: the original survey.
- `assets/references.json`, `assets/verification.json`, `assets/verification.csv`: downloadable bibliography and verification records.

Explanations outside the PDF are editorial syntheses. Diagrams and numerical examples are illustrative. Reference placement follows citations in the survey; a reference may appear in multiple sections. Bibliographic verification is not a review of scientific findings.

The PDF.js files in `assets/` retain their Mozilla Foundation copyright and Apache-2.0 license notices. The survey and cited works retain their respective authors’ rights.

The locally hosted Manrope font is distributed under the SIL Open Font License 1.1; see `assets/fonts/OFL.txt`.
