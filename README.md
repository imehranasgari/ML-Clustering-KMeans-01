# **Customer Segmentation with K-Means Clustering**

---

## **1. Project Title**

**Customer Segmentation using K-Means Clustering**

---

## **2. Problem Statement and Goal of Project**

This project focuses on **segmenting customers into meaningful groups** based on their **demographic and financial attributes**. Accurate segmentation enables:

* Targeted marketing strategies
* Personalized product offerings
* Improved risk management in **financial and retail applications**

The goal is to apply **unsupervised learning** to analyze customer data and uncover hidden patterns that can optimize business strategies.

---

## **3. Solution Approach**

The notebook demonstrates an **end-to-end K-Means clustering workflow**, including:

* **Loading, inspecting, and preprocessing** customer data
* Selecting relevant **numerical features** for clustering
* Applying **K-Means clustering** (with various cluster sizes and the elbow method for choosing optimal k)
* Profiling **clusters** and visualizing the results using both **2D** and **3D plots**
* **Evaluating clustering quality** with the **Silhouette Score**

This approach emphasizes exploration and optimization, including determining the optimal number of clusters and profiling customer segments.

---

## **4. Technologies & Libraries**

* **Python**
* **NumPy** – numerical computation
* **Pandas** – data manipulation and analysis
* **Matplotlib** – plotting and visualization
* **Scikit-learn** – model training, evaluation (KMeans, Silhouette Score)
* **Plotly** – interactive visualizations for deeper analysis

---

## **5. Description about Dataset**

* **Source**: Uploaded **CSV file** (`customer_data.csv`)
* **Columns**:

  * `Customer Id`, `Age`, `Edu`, `Years Employed`, `Income`, `Card Debt`, `Other Debt`, `Defaulted`, `DebtIncomeRatio`, `Address`
* **Content**: Each row contains demographic data (age, education), employment history, income, debts, and default status for individual customers.

---

## **6. Installation & Execution Guide**

**Prerequisites**:

* Python 3.x
* Jupyter Notebook or JupyterLab

### **Clone the repository**:

```
git clone <repository_url>
cd <repository_directory>
```

### **Install required dependencies**:

```
pip install numpy pandas matplotlib scikit-learn plotly
```

### **Run the notebook**:

```
jupyter notebook k-means.ipynb
```

---

## **7. Key Results / Performance**

* **Elbow Method**: Identified the optimal number of clusters using geometric analysis and the **Sum of Squared Errors (SSE)** curve.
* **Silhouette Score**: Used to evaluate clustering quality for the selected number of clusters, ensuring robust segmentation.
* **Cluster Profiling**: Examined clusters to reveal segments with distinct characteristics (age, income, education, debt ratios).
* **Visualization**:

  * **2D/3D scatter plots** to show clear separation between clusters
  * **Centroid overlay** (red 'X') for visualizing cluster centers.

---

## **8. Screenshots / Sample Outputs**

* **Cluster Scatter Plots**: Visual representations of customer segments based on clustering results.
* **Centroid Overlay**: Visual markers showing the center of each cluster.
* **Elbow Method Plot**: SSE vs. number of clusters, annotated with the optimal point.
* **Interactive Plotly Visualizations**: Detailed interactive plots for deeper cluster analysis.

> 💡 *Some interactive outputs (e.g., plots, widgets) may not display correctly on GitHub. If so, please view this notebook via [nbviewer.org](https://nbviewer.org) for full rendering.*

---

## **9. Additional Learnings / Reflections**

* Experimented with **cluster selection techniques**, including the **elbow** and **silhouette methods**.
* Emphasized the importance of **feature scaling** for effective clustering.
* **Visualization** plays a key role in improving the interpretability of the clustering results, making it easier to communicate insights.
* The notebook structure provides a robust approach for **unsupervised learning workflows**, offering valuable insights into customer behavior and segmentation.

---

## **👤 Author**

**Mehran Asgari**
**Email:** [imehranasgari@gmail.com](mailto:imehranasgari@gmail.com)
**GitHub:** [https://github.com/imehranasgari](https://github.com/imehranasgari)

---

## **📄 License**

This project is licensed under the **MIT License** – see the `LICENSE` file for details.

---

> 💡 *Some interactive outputs (e.g., plots, widgets) may not display correctly on GitHub. If so, please view this notebook via [nbviewer.org](https://nbviewer.org) for full rendering.*

---

