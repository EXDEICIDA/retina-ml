<p>
  <a href="https://choosealicense.com/licenses/mit/"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="MIT License"></a>
  <img src="https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54" alt="Python">
  <img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?logo=scikit-learn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/pandas-%23150458.svg?logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Colab-F9AB00?logo=googlecolab&color=525252" alt="Google Colab">
  <img src="https://img.shields.io/badge/Kaggle-035a7d?logo=kaggle&logoColor=white" alt="Kaggle">
</p>

# Retina ML

This project builds a complete machine learning pipeline to predict DNA methylation status based on genomic features. The goal is to identify epigenetic patterns that can serve as early detection biomarkers for rare genetic vision disorders, such as Retinitis Pigmentosa.

## Results
After evaluating multiple algorithms, a simple linear model outperformed complex tree-based models, indicating that the feature boundaries in this specific dataset are highly linear. 
* **Winning Model:** Logistic Regression
* **Accuracy:** 97.00%

## Dataset
The data is sourced from the Kaggle dataset: DNA Methylation Data - Epigenetic Biomarkers. It contains 1,000 samples with four key genomic features.

| Feature Name | Type | Description |
|---|---|---|
| **`cpg_density`** | Genomic Feature | The density or concentration of CpG sites in the specific genomic region. |
| **`genomic_location`** | Genomic Feature | The normalized physical position of the site within the chromosome. |
| **`regulatory_score`** | Genomic Feature | A metric indicating the potential regulatory activity (like promoters or enhancers) of the region. |
| **`conservation_score`** | Genomic Feature | A score representing how well this genomic sequence has been preserved across evolution. |
| **`methylation_status`** | Target Variable | The binary classification target (0 = Unmethylated, 1 = Methylated). |
