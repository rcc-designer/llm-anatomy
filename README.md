# The Anatomy of an LLM

**From Raw Data to Intelligence: The Training Pipeline, Resources, and Real Costs of Generative AI**

Romires Campelo · AIML-501: Model Development · Indiana Wesleyan University

## Open or deploy

Open `dist/index.html` in a browser. All runtime files are local and require no build, account, API key, package installation, or backend. `dist/` is the ready-to-deploy site and contains the editable HTML, CSS, JavaScript, and vector diagram. Keep these files together. The Python generator `build.py` is optional; it regenerates the main HTML and training SVG. `assets.py` regenerates publication artwork and needs CairoSVG only if artwork is rebuilt.

- `dist/index.html`: presentation content and semantic structure.
- `dist/style.css`: responsive, accessible focus, reduced-motion, and print styles.
- `dist/app.js`: pipeline, model selector, comparisons, calculator, and print handling.
- `dist/training.svg`: original training-loop diagram.
- `publication/`: cover artwork and proposed portfolio placement screenshot.
- `PUBLICATION_GUIDE.md`: copy-ready portfolio text and integration steps.
- `QA_AND_RUBRIC.md`: verification results and rubric mapping.

The presentation is historical and release-specific. Review citations when revising claims. Do not replace missing figures with zero. The personal reflection is explicitly a proposed draft for the author to review before submission.

## Editing

Edit HTML directly for a small change, or edit `build.py` and regenerate with `python3 build.py`. Model case facts and chart metrics live in `dist/app.js`. If you regenerate the HTML after a direct HTML edit, the generator will overwrite that edit. No production Python runtime is needed.

## Publication scope

The supplied Google Sites placement is a labeled local illustration. It does not represent a completed Google Sites edit. Preserve the existing artifact titles and numbering. Source references remain external links; the learning page itself works offline.
