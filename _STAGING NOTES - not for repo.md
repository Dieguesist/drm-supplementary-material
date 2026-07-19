# T10 staging notes (INTERNAL, never upload this file)

Written 11 Jul 2026. The raw evaluation data no longer exists. The three evaluation CSVs were reconstructed from published figures and triangulated; this note documents provenance so the numbers can be defended if a reviewer recomputes them. It must NOT enter the repository: it references the dissertation, which names an author and the university.

## Provenance and verification

Sources: manuscript figures (artifactscoreevaluation.png, archimatefamiliarity.png) and dissertation of Daniel Ramalho (IST, ref. 83441), Figures 5.18 to 5.22. The manuscript and dissertation charts show identical distributions.

Triangulation performed: for every question, the low-familiarity distribution (Fig 5.21, n=14) plus the high-familiarity distribution (Fig 5.22, n=9) equals the overall distribution (Fig 5.19, n=23). All row sums check (14, 9, 23). Familiarity distribution (6, 8, 4, 4, 1) sums to 23 with mean 55/23 = 2.39, matching the reported 2.4. Group sizes match the published split (14 with familiarity 2 or less, 9 with 3 or more).

Recomputed means: Q1 3.74, Q2 4.22, Q3 4.17, Q4 4.09.

## Known error to fix in the manuscript

Figure "Average Question Scores" (questionscoreaverage2.png) labels Q4 as 4.01. The correct value is 94/23 = 4.09. With 23 integer responses, 4.01 is impossible (92/23 = 4.00, 93/23 = 4.04). The error originates in dissertation Figure 5.20 and was carried over. Action: regenerate questionscoreaverage2.png with 4.09 during the figure re-export pass, before or together with the repo upload, so figure and CSV agree.

## Status 11 Jul 2026 (evening)

DONE: three evaluation CSVs (incl. familiarity split, André approved inclusion); interview-guide.pdf rendered with clean metadata (source text in "_interview-guide source" file, André still to review wording); README updated for the split CSV; three evaluation charts regenerated at 300 dpi with corrected Q4 = 4.09 (in /figures; metadata stripped; leak scan of staged files clean). Strategy confirmed: single clean commit, push once when complete.

STILL MISSING (all on André):
/models: drm-v1.archimate, drm-v2.archimate, case-a.archimate, case-b.archimate (then sanitize per checklist)
/coding: concept-coding-scheme.csv (source needed)
/figures: high-resolution Archi re-exports of the model/case figures (evaluation charts already done here)

MANUSCRIPT FOLLOW-UP: replace Figs/questionscoreaverage2.png in Overleaf with the corrected chart (4.09, not 4.01); optionally also the other two regenerated charts for the figure-quality comment.
