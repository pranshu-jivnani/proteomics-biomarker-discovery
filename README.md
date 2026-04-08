# Proteomics Biomarker Discovery in Breast Cancer

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python)
![Scipy](https://img.shields.io/badge/Scipy-Statistics-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Domain](https://img.shields.io/badge/Domain-Proteomics-purple)

## 📌 Project Overview

This project applies statistical analysis and data visualisation to identify differentially expressed protein biomarkers in breast cancer. Using simulated mass spectrometry proteomics data modelled on published literature, the analysis identifies candidate biomarkers that distinguish tumour from normal samples.

---

## 🎯 Research Question

> Can we identify potential protein biomarkers that differentiate breast cancer tumour samples from normal samples using mass spectrometry proteomics data?

---

## 📊 Dataset

| Parameter | Value |
|---|---|
| Tumour samples | 30 |
| Normal samples | 15 |
| Total proteins | 200 |
| Known cancer proteins | 20 |
| Data type | Simulated MS proteomics |

---

## 🛠️ Tools & Libraries

| Category | Tools |
|---|---|
| Language | Python 3 |
| Statistics | Scipy, NumPy |
| Data Handling | Pandas |
| Visualisation | Matplotlib, Seaborn |

---

## 🔬 Methodology

1. **Data Generation** — Simulated proteomics dataset based on published breast cancer literature
2. **Statistical Testing** — Independent t-tests for each protein (tumour vs normal)
3. **Volcano Plot** — Visualised fold change vs statistical significance
4. **Heatmap** — Expression patterns of top 20 proteins across all samples
5. **Biomarker Ranking** — Ranked proteins by p-value and fold change
6. **Export** — Results saved as CSV for reproducibility

---

## 📈 Key Results

- **194 out of 200** proteins showed significant differential expression (p < 0.05)
- **Top biomarker candidates:** VEGFA, HER2, MYC, EGFR, MKI67
- **VEGFA** showed highest fold change (5.98) key driver of tumour angiogenesis
- **HER2** upregulation (4.97) consistent with HER2-positive breast cancer
- Results consistent with published breast cancer proteomics literature

---

## 🧬 Top Biomarker Candidates

| Protein | Fold Change | Biological Role |
|---|---|---|
| VEGFA | 5.98 | Tumour angiogenesis |
| HER2 | 4.97 | Cell proliferation, therapeutic target |
| MYC | 5.63 | Proto-oncogene, poor prognosis marker |
| EGFR | 4.79 | Cell growth, therapeutic target |
| MKI67 | 4.72 | Proliferation marker |

---

## 📁 Repository Structure

- **notebook/** — Jupyter notebook with full analysis
- **results/** — Output figures and CSV files
- **README.md** — Project documentation

---

## 🔗 Related Projects

👉 [Breast Cancer RNA-seq Analysis (R)](https://github.com/pranshu-jivnani/breast-cancer-rnaseq-tcga)
👉 [BRCA Sequence Conservation (Python)](https://github.com/pranshu-jivnani/brca-sequence-conservation-python)
👉 [NGS Variant Calling Pipeline (Linux)](https://github.com/pranshu-jivnani/ngs-variant-calling-pipeline)

---

## 👤 Author

**Pranshu Jivnani**
MSc Bioinformatics — Teesside University, Middlesbrough, UK
📧 connect.pranshu19@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/pranshu-jivnani)

---

## 📄 License

This project is licensed under the MIT License.
