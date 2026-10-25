# SWYNEX-Biological-Dataset-Selection
Selection and documentation of a small public biological dataset for SWYNEX internship Task 1.

## Project Overview

This repository documents the selection of a public biological dataset as part of Task 1 of the SWYNEX Technologies internship.

## Dataset Information

- **Dataset title:** Gene expression difference of small cell lung cancer cell after treatment with a kind of drug
- **GEO accession:** GSE66625
- **Repository:** NCBI Gene Expression Omnibus (GEO)
- **Organism:** Homo sapiens
- **Cell line:** NCI-H446
- **Experiment type:** Expression profiling by microarray
- **Platform:** GPL16951 — Phalanx Human OneArray Ver. 6 Release 1
- **Total samples:** 6
- **Control samples:** 3 (DMSO)
- **Drug-treated samples:** 3
- **Raw supplementary archive:** GSE66625_RAW.tar (9.5 MB, as reported by GEO)

## Research Question

Which genes show differential expression between DMSO-treated control samples and drug-treated NCI-H446 small-cell lung cancer cells?

## Sample Information

| Group | GEO sample IDs | Sample count |
|---|---|---:|
| Control (DMSO) | GSM1626567, GSM1626568, GSM1626569 | 3 |
| Drug-treated | GSM1626570, GSM1626571, GSM1626572 | 3 |

## Why This Dataset Was Selected

- It contains a manageable number of biological samples.
- It provides a clearly defined control-versus-treatment comparison.
- It is publicly available through NCBI GEO.
- Its reported supplementary archive is relatively small.
- It provides an opportunity to learn about biological metadata, gene-expression data, and differential expression analysis.

## Planned Work

1. Verify the dataset metadata and sample annotations.
2. Inspect the available processed expression data.
3. Document the data format and relevant metadata.
4. Identify suitable downstream analyses, if appropriate for the available data.

## Limitations

The study contains only three samples per group. Any statistical conclusions must account for the small sample size. The identity of the drug and further experimental details should be verified from the original GEO record and associated files before interpretation.

## References

1. NCBI GEO Series GSE66625: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE66625
2. NCBI GEO Platform GPL16951: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GPL16951
3. NCBI GEO sample records: GSM1626567–GSM1626572

---

*Prepared for SWYNEX Technologies internship Task 1: Biological Dataset Selection.*
