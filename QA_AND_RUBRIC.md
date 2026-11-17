# Verification and rubric alignment

Reviewed November 16, 2026. This is a quality checklist, not a prediction of the instructor’s score.

| Rubric criterion | Maximum | Implementation evidence |
|---|---:|---|
| Clarity and Organization | 10 | Eight numbered sections; training/inference distinction; fixed section navigation |
| Visual Appeal and Professionalism | 8 | Navy/white palette linked to the existing portfolio; original SVG; restrained grid and typography |
| Technical Execution | 7 | Lightweight static site; responsive controls; labeled inputs; keyboard focus; reduced-motion and print styles |
| Classification Accuracy | 10 | Stages, resources, quality effects, and case-study evidence kept distinct |
| Representation of Relationships | 8 | Input/output stage panels; stage-resource mapping; feedback loop; trade-off relationships |
| Comprehensiveness | 7 | Seven lifecycle stages, five resource categories, four named models, estimator, synthesis and sources |
| Explanation of Classification Process | 8 | Dedicated organization note explains rationale and boundary cases |
| Reflection on Learning | 9 | First-person draft connects networking, utilization, evidence scope, and responsible engineering; author review explicitly required |
| Writing Quality | 8 | English academic prose, source notes, consistent author–date references with numbered cross-links |
| Total | 75 | No guaranteed score claimed |

## Tests performed

- JavaScript syntax check passed with Node.
- All seven stage buttons show the corresponding panel. Keyboard Enter on “Show all stage details” exposed all seven.
- All four model selectors reveal the correct case; only one is visible on screen. An initial hidden-panel CSS conflict was found and corrected.
- All four comparison metrics render matching titles and labels. Missing observations remain text plus a hatched area, never a zero-valued bar.
- Calculator default: 1,024 GPUs × 30 days × 24 = 737,280 GPU-hours; at $3/hour, rental is $2,211,840. Energy at 700 W and PUE 1.2 is 619,315.2 kWh; at $0.12/kWh, $74,317.824 before rounding.
- Calculator boundary: one GPU for one day returns 24 GPU-hours and $72 at the default rental rate. Zero GPUs triggers validation and clears numerical results. Reset restores the defaults.
- Desktop screenshot reviewed. Mobile (390px iframe) and tablet (768px iframe) rendered the actual site. Measured body widths equaled scroll widths (375/375 and 753/753 excluding scrollbars), with no whole-page horizontal overflow. Wide data table scrolls within its own region.
- Browser-visible headings and controls inspected; button state exposed with aria-pressed, results with polite live regions, SVG with descriptive text, and inputs with labels. Not a formal assistive-technology or WCAG certification.
- All 12 external links in the presentation returned HTTP 200 during verification. This does not guarantee future availability.
- Print stylesheet exposes all stage and model details; before-print handler expands research notes. Print pagination and physical printer output have not been exhaustively tested.
- Runtime has no external scripts, fonts, analytics, API calls, backend, or paid dependencies. Authoritative references open only when selected.
- Google Sites integration itself has not been executed. The placement screenshot is explicitly an illustration; iframe behavior was checked locally.

## Academic checks

- Llama 405B is separated from the model family total; GPU-hours are cumulative device time.
- The observed reliability window is not reported as the full training duration.
- Cost comparisons share the AI Index cloud-compute-rental basis and identify inflation adjustment.
- Location- and market-based emissions are not mixed in one chart.
- Claude company infrastructure announcements are not represented as single-model spending.
- Personal reflection is a draft requiring author review; no frontier training or unperformed experiment is attributed to the student.
- Full APA 7 long-author-list formatting is not claimed: long author lists use “et al.” consistently in the on-page bibliography.
