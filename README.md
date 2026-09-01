# metaNPSpublic

Public companion repository for the **metaNPS** (meta nutrient-profiling) work.

## Contents

| File | What it is |
|------|------------|
| [`metaNPS_expert_HO_top100v2.html`](metaNPS_expert_HO_top100v2.html) | A self-contained interactive figure (an exported R `htmlwidgets` bundle — plotly + DataTables + leaflet). All JavaScript, CSS, and data are embedded inline. |

## How to view

No build step or dependencies are required. **Download the HTML file and open it in any modern web browser** (or use the GitHub "Raw" view). The figure renders entirely client-side.

## What this is

Restricted tool build for the [FRESH website](https://www.freshfoodrecs.com), based on the
foundational meta-NPS methodology paper —

> Erndt-Marino, J., O'Hearn, M., & Menichetti, G. (2023). *An integrative analytical framework to
> identify healthy, impactful, and equitable foods: a case study on 100% orange juice.*
> International Journal of Food Sciences and Nutrition, 74(6), 668–684.
> [DOI 10.1080/09637486.2023.2241672](https://doi.org/10.1080/09637486.2023.2241672)

`HO` = expert hold-out subset; `top100` = 100 foods presented in the tool.

## Reproducibility

Generating source and data are not in this repository. The meta-NPS methodology substrate lives
in the private `fresh_food` repo; the harmonization pipeline + scoring code + underlying inputs
are Bespoke background IP. This public release is the rendered artifact only — an interactive
companion to the 2023 paper made available on the FRESH website.

## License

Released under [CC BY 4.0](LICENSE) — you may share and adapt with attribution.
