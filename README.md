# Customer-Segmentation
Machine Learning Internship Projects –  Customer Segmentation
## Task 2: Customer Segmentation

**Objective:**  
Cluster mall customers into different groups based on their **Annual Income** and **Spending Score** to understand shopping behaviors.

**Dataset:**  
- Mall Customers dataset (Kaggle)  
- Features used:  
  - Annual Income (k$)  
  - Spending Score (1–100)  

**Steps Performed:**  
1. Data loading and inspection  
2. Feature selection (Income & Spending Score)  
3. Data scaling using `StandardScaler`  
4. Visual exploration of customer distribution  
5. Applied **K-Means clustering**  
   - Used **Elbow method** and **Silhouette score** to find optimal K  
6. Visualized clusters with centroids  
7. Analyzed average spending per cluster  
8. Bonus: Implemented **DBSCAN** clustering for comparison  

**Tools & Libraries:**  
- Python, Pandas, Matplotlib, Seaborn  
- Scikit-learn (KMeans, DBSCAN, StandardScaler)  

**Results:**  
- Customers were grouped into meaningful clusters such as:  
  - High Income, High Spending  
  - Low Income, Low Spending  
  - Average Income, Average Spending, etc.  
- Visualization clearly showed natural customer segments  
- This segmentation can help businesses design targeted marketing strategies.  


