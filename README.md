# Staurozoa Evolutionary History

Research repository for the taxon sampling, phylogenetic reconstruction,
divergence-time estimation, historical biogeography, and ancestral niche
reconstruction of Staurozoa.

This repository accompanies a manuscript by Morales-Guerrero et al. that is
currently in preparation.

## Current contents

- Taxon-sampling dataset with 35 taxa and 394 geographic distributions.
- GenBank accession-code workbook for the sampled terminals.
- Interactive HTML distribution catalogue with the same 394 distributions.
- Prepared folders for scripts, results, figures, and documentation.

## Repository structure

| Path | Contents |
| --- | --- |
| `data/taxon_sampling/` | Source Excel workbooks used to define taxon sampling and sequence accessions. |
| `catalogue/` | Interactive HTML distribution catalogue. |
| `scripts/` | Reproducible analysis and data-processing scripts. |
| `results/phylogeny/` | Phylogenetic-analysis outputs. |
| `results/divergence_time/` | Divergence-time estimation outputs. |
| `results/biogeography/` | Historical-biogeography outputs. |
| `results/ancestral_niche_reconstruction/` | Ancestral niche-reconstruction outputs. |
| `figures/` | Final and intermediate manuscript figures. |
| `docs/` | Methods, workflows, metadata, and supporting documentation. |

## Input files

### `Dataset1_11_08_2026.xlsx`

Master taxon-sampling and distribution dataset. The `Dataset S1` worksheet
contains 394 geographic records for 35 taxa, with taxonomy, coordinates,
marine realm, and locality information.

### `GenBank_accession_codes_11_08_2026.xlsx`

GenBank accession codes associated with the terminals used in the study.

### `staurozoa_distribution_catalogue.html`

Self-contained interactive catalogue and distribution map. Download the file
and open it in a web browser to use the interactive filters and map.

## Data consistency

The Excel distribution dataset and HTML catalogue were reconciled on
2026-09-07. Both contain 394 distributions. *Haliclystus borealis* has 15
records, including Mitsu Bay, Japan (40.912668, 140.868546).

The Mitsu Bay observation is currently identified as unpublished in the source
workbook. Its provenance and permission for public release should be confirmed
before this repository is made public.

## Reproducibility

Analysis scripts, software versions, parameters, and commands will be added as
each workflow is finalized. Derived files should be placed in the corresponding
folder under `results/`; source data should remain unchanged.

## License

No license has been selected while the manuscript is in preparation.

