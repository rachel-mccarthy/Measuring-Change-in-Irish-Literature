# Irish Literature Metadata Dataset

## Overview
This dataset contains bibliographic and biographical metadata for a collection of Irish literary works and their authors. It is provided as a CSV file for easy use in spreadsheet software, data analysis tools, and programming workflows.

## Contents
Each row in the CSV represents a single book. The dataset includes the following fields:
- **Author (l, f)** — Author’s name in “last name, first name” format  
- **Book Title** — Full title of the work  
- **DOB - DOD** — Author’s birth and death years (open-ended if still living)  
- **Gender** — Author’s gender  
- **Place of Birth (county in Ireland)** — Irish county of birth (left blank if unknown)
- **Publication Date** — Year the book was first published  
- **Publishers (normalized)** — Standardized name of the publisher  
- **Publisher's Location** — Country in which the publisher released the book  
- **Publication Date Century** — Century classification of publication date
- **Publication Date Quarter-Century** — Quarter-century classification of publication date  
- **Publication Date Decade** — Decade classification of publication date

## Notes
- Missing birth or death years are represented with an open-ended dash (e.g., `1981-` if year of death is unknown, `-1981` if year of birth is unknown). Question marks replace unknown digits (e.g. if an author was known to be born during the 1710s, but their exact year of birth is unknown, it is represented as `171?`).
- Publisher names have been normalised to reduce duplication and variation.  
- Date groupings (century, quarter-century, decade) are derived from the publication year for easier temporal analysis.

## Citation
If you use this dataset in academic or published work, please cite the creator and project associated with the dataset..

## Acknowledgements
This corpus was curated by researchers on the CASCADE project: https://www.horizoncascade.net/
CASCADE (101119511) is a Horizon Europe MSCA Doctoral Network funded by the European Commission and UKRI.
