#Joint Causal Effects of Time-Varying TRAP Mixtures and Environmental Justice


This folder includes **reproducible R code** for the **Joint Causal Effects of Time-Varying Traffic-Related Air Pollution Mixtures on Nonaccidental Mortality and Environmental Justice Implications: A Population-Based Cohort Study in Toronto, Canada** Manuscript Analysis and Visualization.

**Authors**: Juwel Rana, Alexander P. Keil, Hong Chen, Chen Chen, Marianne Hatzopoulou, Jad Zalzal, Tarik Benmarhnia, Jay S. Kaufman

Raw microdata, census extracts, and large derived datasets are **not** included.

## Related work

- Public analysis builds on standard R packages such as `sf`, `data.table`, and `tvcQGComp`.

## Repository layout

| Path | Purpose |
|------|---------|
| `scripts/` | Main analysis pipelines (add sanitized `.R` files here) |
| `data/README.md` | How to obtain restricted inputs locally |
| `CITATION.cff` | Software and manuscript citation metadata |

## Data availability and privacy

Census, exposure, and health-linked inputs are **not** included here. 

- CanCHEC Cohort data are accessible through Statistics Canada's Research Data Center program. Environmental exposure data are available upon request to the original authors.
- A toy dataset is included for replication purposes

See `.gitignore` for excluded file types.

## Requirements

- R (>= 4.2 recommended)
- Key packages: `sf`, `data.table`, `ggplot2`, `qgcomp`, and others as noted in scripts

## Acknowledgments
This study was funded by Health Canada under the Air Quality Program of the Government of Canada.

## Citation

**APA**

>Rana, J., Keil, A. P., Chen, H., Chen, C., Hatzopoulou, M., Zalzal, J., Benmarhnia, T., & Kaufman, J. S. (2026). *Joint causal effects of time-varying traffic-related air pollution mixtures on nonaccidental mortality and environmental justice implications: A population-based cohort study in Toronto, Canada* [Under Review].

## Contact

Juwel Rana — juwelrana@saistbd.org
