# wines-clustering-analysis
# 🍷 Wine Industry Clustering Analysis

Proyecto de análisis no supervisado orientado a la segmentación económica de bodegas españolas mediante técnicas de clustering.

El objetivo es identificar perfiles homogéneos de bodegas que reflejen distintos modelos de negocio dentro del sector vitivinícola, combinando rigor estadístico e interpretación económica.

---

## 📌 Project Overview

- **Type**: Unsupervised Learning / Clustering
- **Domain**: Business Intelligence / Economic Analysis
- **Tools**: R
- **Techniques**: k-means, k-medoids, hierarchical clustering, PCA, cluster validation

---

## 📊 Methodology

1. Data cleaning and preprocessing  
   - Treatment of missing values  
   - Detection and removal of outliers  
   - Feature selection  

2. Exploratory analysis and clustering tendency  
   - Hopkins statistic  

3. Clustering techniques  
   - Hierarchical clustering (Ward)  
   - Partitioning methods (k-means, PAM)  

4. Model validation  
   - Silhouette coefficient  
   - Internal and stability measures (clValid)  

5. Interpretation  
   - Principal Component Analysis (PCA)  
   - Cluster profiling  

---

## 📈 Key Results

- Identification of **six clearly differentiated economic clusters**
- Strong heterogeneity in size, profitability, and efficiency across wineries
- Robust cluster structure validated using multiple criteria

---

## 🧰 Tools & Libraries

- R  
- tidyverse  
- cluster  
- factoextra  
- clValid  

---

## 📂 Repository Structure

```text
wine-clustering-analysis/
├── data/
├── analysis/
├── output/
