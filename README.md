# -cSMA-26-Pinterest
## Authors: 
Sophia Babl (sophia.babl@stud.uni-regensburg.de)  
Emily Heinz (emily.heinz@stud.uni-regensburg.de)  
Teresa Holler (teresa.holler@stud.uni-regensburg.de)

**Institution:** University of Regensburg, Faculty of Language, Literature and Cultural Studies 

**Course:** Computational Social Media Analysis (Winter 2025/26)

**Submission Date:** March 20, 2026

## Overview
This is the repository contains the code, data and analysis for our computational study of two contrasting Pinterest aesthetics: **Clean Girl** and **Messy Girl**. We examine how visual and textual signals construct consumption identities on Pinterest through a mixed-methods approach combining manual annotation, computer vision (color analysis), and natural language processing (OCR + text analysis).

**Research Questions**
1. How do visual aesthetics (color palettes, composition, body representation) differ between Clean Girl and Messy Girl trends?
2. What textual patterns (brands, products, instructions) characterize each aesthetic?
3. To what extent do these trends reproduce exclusionary norms around body image, skin color, and consumption?

## Repository Structure
data:

- Annotation_Overall.xlsx
- 
- combined_clean_messy_new.csv

notebooks:

- textual
results
README.txt
requirements.txt

## Acknowledgments
- **Base Preprocessing Notebook:** Adapted from Michael Achmann-Denkler's [social-media-lab](https://github.com/michaelachmann/social-media-lab) (Achmann-Denkler, 2025, doi: 10.5281/zenodo.8199901)
- **Annotation Tool:** Label Studio (Open Source)
- **Color Analysis:** scikit-image, scikit-learn
- **OCR:** EasyOCR
- **Statistical Analysis:** statsmodels, pandas, seaborn
