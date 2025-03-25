#  Customer Segmentation Using Clustering

This project performs customer segmentation using **K-Means Clustering** on the popular **Mall Customer Segmentation Dataset**. The goal is to identify groups of customers based on their age, income, and spending score to help businesses better target their marketing strategies.

## Dataset

- **Name**: Mall Customer Segmentation Dataset
- **Source**: Kaggle ([Link](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial))
- **Columns**:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

## Project Workflow

1. **Data Exploration**:
   - Viewed column types and basic statistics
   - Plotted distributions (age, gender, income, etc.)

2. **Preprocessing**:
   - Selected key numerical features: Age, Annual Income, and Spending Score
   - Scaled features using `StandardScaler`

3. **Clustering**:
   - Applied **K-Means Clustering**
   - Used **Elbow Method** to find the optimal number of clusters (k=5)
   - Visualized clusters using **PCA** (2D projection)

4. **Analysis**:
   - Interpreted cluster groups based on average age, income, and spending behavior

## Results

- Identified 5 distinct customer groups
- Plotted the clusters with colored visualizations
- Provided business insights for each cluster

## Technologies Used

- Python, Pandas, Matplotlib, Seaborn
- Scikit-learn (KMeans, PCA, StandardScaler)

---

