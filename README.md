# AI-Based Sequential Hybrid Clustering Model for Restaurant Menu Segmentation

## Overview
This repository contains the source code for an AI-Based Sequential Hybrid Clustering Model for Restaurant Menu Segmentation (ICDEES 2026). The proposed approach combines K-Means clustering, Menu Engineering analysis, and K-Modes clustering to identify menu segments based on numerical and categorical characteristics.

## Methodology
The workflow consists of three main stages:
1. **K-Means Clustering:** Groups menu items based on numerical features such as Amount, Frequency, Recency, and Profit.
2. **Menu Engineering:** Classifies menu items into four categories: Star, Horse, Puzzle, and Dog.
3. **K-Modes Clustering:** Combines the resulting categorical labels to generate the final menu segments.

## Repository Structure
- `kmeans_clustering.py` — K-Means clustering.
- `menu_engineering.py` — Menu Engineering.
- `kmodes_clustering.py` — Final K-Modes clustering.

## Dataset Availability
Transaction data for Kaja Kangin Warung are included in this repository. However, the transaction data for Ely’s Kitchen are not publicly available due to business confidentiality and privacy restrictions. The repository provides the implementation code for the proposed sequential hybrid clustering approach, while access to Ely’s Kitchen data and related confidential outputs is restricted.
