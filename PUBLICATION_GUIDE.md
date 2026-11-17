# Publishing and portfolio integration

Published presentation: https://anatomy-llm-romires.campelogpt.chatgpt.site

Publication verified November 16, 2026. Public access enabled. Google Sites itself was not edited.

## Copy-ready portfolio entry

**Title:** The Anatomy of an LLM

**Subtitle:** From Raw Data to Intelligence: The Training Pipeline, Resources, and Real Costs of Generative AI

**Description:** Explore how large language models are trained—from raw data to deployment. An interactive pipeline, sourced model comparisons, and a resource lab reveal the engineering trade-offs behind generative AI.

**Objective:** Explain the stages and resource requirements of LLM development while distinguishing official disclosures, independent estimates, derived calculations, and undisclosed information.

**Process:** Organize the lifecycle into seven stages; connect five resource categories to those stages; examine release-specific evidence for Llama 3.1 405B, GPT-4, Gemini 1.0 Ultra, and Claude 3 Opus; explore cost assumptions through a transparent calculator.

**Tools and technologies:** Semantic HTML, responsive CSS, vanilla JavaScript, original SVG diagrams, official model reports, and the Stanford AI Index.

**Value proposition:** A visual explanation that connects model development to data quality, distributed computing, networking, resource efficiency, and responsible AI.

**Unique value:** Traceable evidence labels and explicit accounting boundaries prevent comparisons that mix GPU time, rental cost, emissions, and total corporate investment.

**Cover:** `publication/Anatomy_LLM_Cover.png` (1600 × 900). Use “fit” rather than cropping to keep the title visible. Vector original also included.

## Option A — Vercel

1. Extract the ZIP and create a GitHub repository with the project contents.
2. In Vercel, choose Add New → Project and import that repository.
3. Select the **Other** framework preset. Use the repository root, leave the build command empty, and set the output directory to `dist`.
4. Deploy. Open the returned deployment URL and test pipeline buttons and calculator.
5. Verify the production page can be opened without authentication before embedding it in a public portfolio. No environment variables are required.

The included `vercel.json` declares `dist` as the output directory. Documentation: https://vercel.com/docs/frameworks

## Option B — GitHub Pages

1. Create a public repository for this artifact.
2. Upload the **contents of `dist/`** to the repository root (not a parent folder). Include `.nojekyll`.
3. Open Settings → Pages. Under Build and deployment, select Deploy from a branch.
4. Select `main` and `/ (root)`, then save.
5. Wait for the Pages deployment and open the exact URL GitHub displays. Relative asset paths support a repository subpath.

Documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Add to Google Sites

1. Open the portfolio editor and create a new child page under Artifacts named **The Anatomy of an LLM**.
2. Add the title and description above. Do not renumber or replace existing artifacts.
3. Choose Insert → Embed and paste the deployed public URL. Insert the preview.
4. Make the embed full width and start with approximately 900–1100 pixels of height. The presentation scrolls internally; Google Sites does not automatically resize a cross-origin iframe to its entire content height.
5. Alternatively choose Embed code and use the snippet below, replacing `YOUR_PUBLIC_URL` with the verified URL.
6. Add an **Open full presentation** button using the same URL. This is the fallback if the hosting service restricts framing or a mobile visitor prefers a full browser tab.
7. On the Artifacts index, add the supplied cover, linked title, and short description alongside the latest artifacts. The supplied screenshot shows a proposed layout, with prior covers represented schematically.
8. Preview desktop and mobile, publish Google Sites, then verify the published page and embedded interactions in a signed-out browser.

```html
<iframe
  src="https://anatomy-llm-romires.campelogpt.chatgpt.site"
  title="The Anatomy of an LLM — interactive presentation"
  width="100%"
  height="1000"
  style="border:0; max-width:100%;"
  loading="lazy">
</iframe>
```

Documentation: https://support.google.com/sites/answer/90569

## Before academic submission

Review the first-person Learning Reflection and adapt it to your own learning. The draft does not claim you trained a frontier model or performed the cited experiments. Use Print / save as PDF to expand stage details and model cases for a printable view. Browser print settings can affect pagination; inspect the print preview.

The Google Sites portfolio has not been modified by this package.
