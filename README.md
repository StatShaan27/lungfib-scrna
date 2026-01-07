# LungFib scRNA-seq

**Single-cell RNA sequencing analysis of innate immune cell states in lung fibrosis, with a focus on transcriptional programs and regulatory factors underlying pro-fibrotic activation.**

---

## Project Overview

Chronic lung injury and inflammation can drive fibrosis through aberrant activation of innate immune cells such as macrophages, neutrophils, and dendritic cells. While bulk transcriptomic studies have identified fibrosis-associated pathways, the **cell-type–specific transcriptional programs and regulatory mechanisms** governing pro-fibrotic immune states remain incompletely characterized.

This project uses **single-cell RNA sequencing (scRNA-seq)** to:
- Identify immune cell subpopulations associated with pro-fibrotic states in lung tissue
- Characterize their gene expression signatures at single-cell resolution
- Explore regulatory transcription factors and pathways implicated in fibrosis

The repository is designed as a **tutorial-style, reproducible research notebook**, supporting both methodological learning (R / Seurat / scRNA-seq analysis) and biologically driven discovery.

---

## Scope and Status

- **Data**: Public scRNA-seq datasets (initial phase); future integration with experimental data anticipated  
- **Species**: Likely mouse lung tissue (subject to confirmation)  
- **Methods**: R, Seurat, downstream differential expression and pathway/regulatory analyses  
- **Status**: Ongoing (living repository)

All interpretations are treated as provisional unless explicitly stated otherwise.

---

## Repository Structure
/
├── biology/ # Biological background and motivation
├── scrna-seq-basics/ # Conceptual foundations of scRNA-seq
├── data/ # Dataset descriptions and metadata
├── seurat-tutorial/ # Step-by-step Seurat analysis
├── regulatory-analysis/ # Pathway and transcription factor analysis
├── results/ # Results and biological insights
├── reading-log/ # Papers, books, and learning notes
├── reproducibility/ # Code, environments, and rerun instructions
└── team/ # Contributors and acknowledgements

---

## Design Philosophy

- **Explain concepts as they appear** (tutorial-style)
- **Separate narrative from code**, while keeping full reproducibility
- **Avoid overclaiming**; explicitly state assumptions and limitations
- **Optimize for longevity** (MSc → publication → PhD applications)

---

## Website

This repository is paired with a GitHub Pages website that hosts the rendered documentation and figures:

> https://statshaan27.github.io/lungfib-scrna/

---

## Contributors

- Angik  
- Sagnik  
- Shaan  

**Supervision:** Prof. Aritra Bhattacharya  
Human Genetics Unit, Indian Statistical Institute, Kolkata


---

## License

This project is released under the **MIT License**. See `LICENSE` for details.

