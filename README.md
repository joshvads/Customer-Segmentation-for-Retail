# Customer Segmentation using RFM Analysis and Clustering

This project uses **RFM (Recency, Frequency, Monetary)** analysis and **clustering** techniques to segment customers based on their purchasing behavior. We employ clustering models, including **K-Means** and **DBSCAN**, to segment customers into different categories for targeted marketing strategies.

## **Project Structure:**
The project contains the following components:
- **Data Preprocessing**
- **RFM Calculation**
- **Clustering Models**
- **Dimensionality Reduction**
- **Visualization**
- **Marketing Strategy Recommendation**

## **Tasks in this Project:**

### 1. **Data Preprocessing**
   - **Task**: Load the dataset and clean the data.
   - **Description**: This step involves reading the dataset, checking for missing values, and ensuring data integrity. The customer data is cleaned to ensure it is ready for analysis and clustering.

### 2. **RFM Calculation**
   - **Task**: Calculate Recency, Frequency, and Monetary values for each customer.
   - **Description**: RFM metrics are calculated using transaction data. Recency measures how recently a customer made a purchase, Frequency measures how often they make a purchase, and Monetary measures how much they spend.

### 3. **Clustering Models**
   - **Task**: Apply clustering algorithms to segment customers.
   - **Description**: The **K-Means** and **DBSCAN** clustering algorithms are applied to the normalized RFM data. K-Means segments customers into predefined clusters, while DBSCAN identifies dense regions in the data.

### 4. **Dimensionality Reduction**
   - **Task**: Reduce the dimensionality of the data for better visualization.
   - **Description**: **PCA (Principal Component Analysis)** and **t-SNE (t-distributed Stochastic Neighbor Embedding)** are used to reduce the dimensions of the dataset for 2D and 3D visualization.

### 5. **Visualization**
   - **Task**: Visualize the clusters formed by the algorithms.
   - **Description**: We visualize the customer segments using scatter plots based on PCA and t-SNE. These visualizations help to understand the clustering results in a 2D or 3D space.

### 6. **Marketing Strategy Recommendation**
   - **Task**: Analyze customer segments and recommend marketing strategies.
   - **Description**: Based on the clusters, specific marketing strategies are suggested for each group. These strategies aim to enhance customer engagement and retention.

## **How to Run the Code:**

### Prerequisites:
- Python 3.8+
Before running the code, ensure you have the following libraries installed:
- `numpy` (for numerical operations)
- `pandas` (for data handling)
- `scikit-learn` (for machine learning models and clustering algorithms)
- `matplotlib` and `seaborn` (for data visualization)

You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
