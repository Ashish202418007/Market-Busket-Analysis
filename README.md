#  Customer Segmentation & Market Basket Analysis Dashboard

###  Data Science | RFM Segmentation | K-Means Clustering | Association Rules | Plotly Dashboard

This project combines **RFM (Recency, Frequency, Monetary) Analysis**, **K-Means Clustering**, and **Market Basket Analysis** to uncover valuable customer insights.  
It includes a fully interactive **Plotly Dashboard** that visualizes customer behavior, clusters, and association rules between purchased products.

---

##  Project Overview

Retail businesses often struggle to understand:
- **Who their best customers are**
- **What products are bought together**
- **How customer segments differ in value and behavior**

This notebook performs a complete **data-driven customer segmentation pipeline**, including:
1.  **RFM Feature Engineering**
2.  **RFM Segmentation & Scoring**
3.  **K-Means Clustering with Silhouette Optimization**
4.  **Market Basket Analysis (Association Rules)**
5.  **Interactive Plotly Dashboard** for visual exploration

---

## Tech Stack

| Category | Tools / Libraries |
|-----------|-------------------|
| **Programming** | Python 3.12+ |
| **Data Analysis** | Pandas, NumPy |
| **Visualization** | Plotly, Seaborn, Matplotlib |
| **Machine Learning** | scikit-learn (KMeans, Silhouette) |
| **Association Rules** | Orange3, orangecontrib.associate |
| **Dashboarding** | Plotly Express |
| **Notebook Environment** | Jupyter Notebook (.ipynb) |

---

## Features

✅ **RFM Analysis**
- Quantile-based segmentation  
- Automated RFM scoring  
- Identification of “Best”, “Lost”, “Loyal” customers  

✅ **K-Means Clustering**
- Normalization using log & standard scaling  
- Cluster optimization using silhouette score  
- Visual cluster separation and snake plots  

✅ **Market Basket Analysis**
- Association rule mining with FP-Growth  
- Interactive rule filtering (lift, confidence, support)  
- Top association rules visualization  

✅ **Plotly Dashboard**
- Combined visualization of:
  - RFM distributions
  - Cluster insights
  - Association rule network / bar plots
- Exportable as `.html` for standalone dashboards

---

## Installation

1. **Clone this repository**
 ```bash
  git clone https://github.com/Ashish202418007/Market-Busket-Analysis.git
 cd Market-Busket-Analysis
 ```

2. **Create and activate a virtual environment**
  ```Bash
   python -m venv venv
   source venv/bin/activate     # (Linux/Mac)
   venv\Scripts\activate        # (Windows)
  ```
3. **Install dependencies**
```bash
pip install -r requirements.txt
```
4. **Run the notebooks under ./notebooks**
5. **View dashboards under figures**
