Does Publisher Volume Matter?
Overview
This repository contains R code for analyzing the relationship between publisher volume and journal metrics in Scopus-indexed journals. The analysis examines how the number of journals a publisher produces relates to metrics like h-index, SJR, and journal quartiles.
Data Requirements

Input files: sjr2023.txt (main data), sjr2023-o.txt (OA data)

These files must be downloaded from the SCImago Journal Rank (SJR) portal: https://www.scimagojr.com/

Packages: dplyr, stringr, reshape, patchwork, ggrepel, tidyr, scales, ggplot2, ggpubr, widyr, corrplot, dunn.test, lme4

Analysis Components

Publisher categorization (V1: 1 journal, V2: 2-9, V3: 10-99, V4: 100+)
Statistical analysis (Kruskal-Wallis tests, correlation analysis, mixed-effects modeling)
Regional and subject area comparisons
OA vs. non-OA journal analysis

Contact
egkim@kmu.ac.kr
