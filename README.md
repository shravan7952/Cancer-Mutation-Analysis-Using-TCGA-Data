# 🧬 Cancer Mutation Analysis Using TCGA Data

This project focuses on analyzing somatic mutation data across 13,276 cancer samples collected from 22 different primary tumor sites. The data was sourced from **The Cancer Genome Atlas (TCGA)** and processed to explore mutation patterns, visualize tumor mutation burden (TMB), and classify cancer types using machine learning.

---

## 📁 Dataset

- **Source**: [The Cancer Genome Atlas (TCGA)](https://www.cancer.gov/tcga)
- **Folder**: `PRIMARY SITES/`  
  Contains 22 `.tsv` files for each cancer type.
- **Merged Files**:
  - `Combined_Oncomatrix_Detailed_with_Site.csv` – contains mutation types like MISSENSE, FRAMESHIFT, etc.
  - `Combined_Oncomatrix_Binary_with_Site.csv` – binary format (1 = mutation present, 0 = absent)
- **Samples**: 13,276
- **Genes Covered**: 400+

---

## 🧾 Objectives

- Merge and clean mutation data
- Calculate **Tumor Mutation Burden (TMB)** per sample
- Visualize mutation trends across primary sites
- Perform **classification** of cancer types using Random Forest
- Generate publication-ready figures and metrics

---

## 🔍 Key Analyses

### ✅ TMB Boxplot
- Shows the distribution of tumor mutation burden across primary sites

### ✅ Top 20 Mutated Genes Heatmap
- Displays the presence of the most frequently mutated genes across 22 primary sites

### ✅ Random Forest Classifier
- Input: Binary mutation matrix  
- Output: Predicted `Primary_Site`  
- Accuracy: **100%** (perfect classification across all 22 sites using full dataset)

### ✅ Confusion Matrix
- Visual confirmation of classifier’s performance

---

## 🛠️ Tools & Libraries

- Python 3.11+
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `glob`, `os`

---

## 📁 Folder Structure

```

├── PRIMARY SITES/
│   └── <PrimarySite>.tsv
├── Combined\_Oncomatrix\_Detailed\_with\_Site.csv
├── Combined\_Oncomatrix\_Binary\_with\_Site.csv
├── TMB\_Boxplot.png
├── Top20\_Gene\_Heatmap.png
├── Confusion\_Matrix.png
├── random\_forest\_report.txt
├── mutation\_analysis.ipynb
└── README.md

```

---

## 📈 Sample Visuals

-  `TMB_Boxplot.png`
-  `Top20_Gene_Heatmap.png`
-  `Confusion_Matrix.png`
-  `Mutation_Heatmap.png`
-  
---

## 📌 Future Enhancements

- Add mutation subtype distributions (e.g., frameshift, nonsense)
- Integrate interactive dashboards using Streamlit
- Explore clustering, PCA/UMAP for visual separation

---

## 🤝 Contributing

Pull requests and forks are welcome. For major changes, open an issue first to discuss what you'd like to change.

---

## 📬 Contact

**Shravan Srikanthan**  
🔗 [LinkedIn](https://www.linkedin.com/in/shravan-s-7b53a494/)  
📧 shravan@0601200.com 

---
