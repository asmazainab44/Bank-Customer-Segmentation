# Bank Customer Segmentation

## Project Overview
This project applies **unsupervised machine learning** techniques to segment bank customers into meaningful groups based on their demographic and transactional attributes.  

The segmentation helps the bank in:
- Identifying high-value customers  
- Personalizing marketing campaigns  
- Improving customer retention strategies  

## Dataset
The dataset contains customer-level information such as:
- **Demographic attributes**: Age, Gender, Region, etc.  
- **Financial attributes**: Balance, Estimated Salary, Credit Score, etc.  
- **Account details**: Number of products, Active status, Exited (churn), etc.  

*(Dataset source: internal bank records / public dataset used for learning — depending on context)*

## ⚙Methodology
1. **Data Preprocessing**
   - Handling missing values  
   - Encoding categorical variables  
   - Feature scaling using `StandardScaler` / `MinMaxScaler`

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots of key features  
   - Correlation analysis  
   - Customer churn trends

3. **Clustering**
   - Applied **K-Means clustering** to group customers  
   - Optimal cluster number chosen using **Elbow method** & **Silhouette score**  

4. **Cluster Profiling**
   - Interpreted each cluster based on demographic and financial characteristics  
   - Provided insights into customer behavior  

## Results & Insights
- Segmented customers into **N clusters** (e.g., high-value, low-engagement, young professionals, etc.)  
- Key insights:
  - Cluster 1: High-income, high-balance, loyal customers  
  - Cluster 2: Younger, low-balance, high churn risk customers  
  - … (customized to your results)  

## Tech Stack
- **Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Environment**: Jupyter Notebook  

   git clone https://github.com/yourusername/bank-customer-segmentation.git
   cd bank-customer-segmentation
