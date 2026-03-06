# Data and R code

This repository contains the dataset and the R code used for statistical analyses in Microplastics reduce population viability without shifting clonal structure in Daphnia pulex.

## Contents
- `data/DATA.xlsx` – dataset used in the analyses (Excel file).
- `code/RCode.docx` – R code used for the analyses (copied from the ERA workflow).

## How to use
1. Download the repository (Code -> Download ZIP) or clone it.
2. Open `code/RCode.docx` and run the code in R/RStudio.
3. The code expects the dataset at: `data/DATA.xlsx`.

## Notes
- If you move files, update paths in the code accordingly (preferably use relative paths such as `data/DATA.xlsx`).
- Sheet names in the Excel file are used directly in `readxl::read_excel()` calls.

## Citation
Please cite this repository as described in `CITATION.cff`.
