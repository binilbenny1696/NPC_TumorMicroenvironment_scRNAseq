# 🧬 NPC_TumorMicroenvironment_scRNAseq

This project presents a **single-cell RNA sequencing (scRNA-seq)** analysis of the **tumor microenvironment (TME)** in **nasopharyngeal carcinoma (NPC)** using the **GSE150430 dataset**. The goal is to map tumor cell heterogeneity, identify subtype-specific transcriptional markers, and assess immune cell presence within the TME.

---

## 🎯 Objectives

- Perform dimensionality reduction and clustering of tumor cells.
- Discover **marker genes** distinguishing two major tumor subtypes.
- Evaluate **immune infiltration** using canonical markers (CD3D, CD14, EPCAM).
- Interpret biological relevance of cluster-specific gene expression.

---

## 🧰 Tools Used

| Category | Tools |
|----------|-------|
| Analysis Pipeline | Seurat (R), Wilcoxon test |
| Dimensionality Reduction | PCA, UMAP |
| Visualization | `ggplot2`, violin plots, feature plots |
| Marker Discovery | `FindMarkers`, DE test |
| Dataset | GSE150430 (NPC tumor scRNA-seq)

---

## 📂 Project Structure


---

## 🔍 Key Findings

| Feature | Result |
|---------|--------|
| Clustering | Two major tumor subtypes identified (Type A, Type B) |
| Marker Genes | Cluster 0: Gene-984, Gene-4973 (proliferative); Cluster 1: Gene-2042, Gene-4423 |
| Immune Infiltration | Minimal expression of CD3D, CD14 – consistent with low immune presence |
| Tumor Heterogeneity | Distinct transcriptional programs suggest functional subtype divergence |

---

## 📚 Dataset Reference

- **GSE150430**: NPC tumor scRNA-seq dataset from GEO

---

## 👨‍💻 Author

**Binil Benny**  
Tumor Profiling | scRNA-seq | Bioinformatics  
GitHub: [@binilbenny1696](https://github.com/binilbenny1696)

---

## 🪪 License

Licensed under the [Creative Commons BY 4.0](https://creativecommons.org/licenses/by/4.0/).
