# 🛍️ Customer Segmentation for UrbanCart Retail Using K-Means Clustering

<img width="1125" height="1125" alt="image" src="https://github.com/user-attachments/assets/ad1c6a0b-af17-4848-b5ea-c7847c4c12f7" />

## 📘 Project Overview
I developed a **customer segmentation model** for **UrbanCart Retail**, a mid-sized retail chain operating across 50 locations in the United States. UrbanCart offers a wide range of products including groceries, clothing, and home essentials.  
Despite its loyal customer base, the company struggled to understand the diverse preferences and behaviors of its customers. To achieve its mission of delivering **tailored shopping experiences**, UrbanCart sought to leverage customer data to improve marketing, inventory management, and customer retention through data-driven insights.

---

## 🧩 Background
UrbanCart Retail’s operations span multiple U.S. cities, serving a wide demographic range. The company’s mission is to deliver personalized shopping experiences by understanding and meeting the unique needs of each customer, with a vision to become a leader in customer-centric retail through **innovation and analytics**.

However, UrbanCart faced a significant challenge: while it collected large amounts of customer transaction data, it lacked the analytical framework to extract meaningful insights. The company needed a way to **segment its customers** based on purchasing behavior and demographic patterns to enable targeted marketing and strategic decision-making.

---

## ❗ Problem Statement
UrbanCart collects extensive customer transaction and demographic data but has limited understanding of how to utilize this information effectively.  
The key business problem was:  
> *How can we segment customers into meaningful groups based on their purchasing behavior and demographic details to inform data-driven business strategies?*

The objective was to use **unsupervised learning techniques**, particularly **K-Means clustering**, to identify distinct customer segments that could drive marketing, loyalty, and inventory decisions.

---

## 💡 Rationale
Customer segmentation is critical for competitive advantage in the retail industry. Through clustering, UrbanCart can:

- 🎯 **Enhance Marketing:** Deliver personalized marketing campaigns to specific customer groups.  
- 🏬 **Optimize Inventory:** Stock products based on the preferences of different customer clusters.  
- 💳 **Boost Loyalty:** Develop customized loyalty programs to improve customer retention and satisfaction.  

By leveraging **data-driven clustering**, UrbanCart can translate raw data into actionable insights and improve operational efficiency.

---

## 🎯 Project Aim
To develop a **K-Means clustering model** that segments UrbanCart customers into distinct, actionable groups, enabling the company to design targeted marketing campaigns, optimize inventory, and strengthen customer loyalty programs.

---

## 🧭 Project Objectives
1. Analyze customer transaction and demographic data.  
2. Clean and preprocess the dataset for clustering.  
3. Handle missing values and encode categorical features.  
4. Scale numerical features for uniform analysis.  
5. Apply **K-Means Clustering** for customer segmentation.  
6. Determine the optimal number of clusters using the **Elbow Method** and **Silhouette Score**.  
7. Visualize and interpret the clusters to derive actionable insights.  
8. Provide business recommendations for marketing, inventory, and loyalty programs.

---

## ⚙️ Methodology

### **1. Data Understanding**
- Explored the dataset to identify numerical and categorical variables.  
- Checked for missing values and irregularities.  

### **2. Data Preparation**
- Imputed missing values using the **median** for numerical features.  
- Removed irrelevant columns that added no analytical value.  
- Encoded categorical variables such as `Gender` and `PreferredCategory` using **Label Encoding**.  
- Scaled numerical features using **StandardScaler** to normalize value ranges before clustering.

### **3. Model Development**
- Applied **K-Means Clustering** for unsupervised segmentation.  
- Used both the **Elbow Method** and **Silhouette Score** to determine the optimal number of clusters (`k = 4`).  
- Re-trained the model using the optimal `k` value and generated cluster labels for each customer.

### **4. Insights and Visualization**
- Analyzed feature distributions across clusters.  
- Created visualizations (cluster distribution plots and relationship maps) to interpret segment characteristics.  
- Developed clear business profiles for each cluster.

---

## 📊 Insights
The clustering model revealed **four major customer segments**, each with unique purchasing behavior and demographic characteristics:

| Cluster | Profile Description |
|----------|--------------------|
| **0** | High-income, high-spending frequent buyers — premium, loyal customers. |
| **1** | Low-income, low-spending infrequent buyers — price-sensitive shoppers responding to discounts. |
| **2** | Young, high-spending occasional buyers — trend-driven, luxury-oriented shoppers. |
| **3** | Mid-income, moderate-spending regular buyers — consistent, reliable core customers. |

These insights empower UrbanCart to:
- Personalize marketing campaigns per customer type.  
- Align inventory with high-demand products by cluster.  
- Design loyalty programs targeted at key customer groups.

---

## 📈 Results and Business Impact
The segmentation framework provided **data-driven clarity** on UrbanCart’s customer base, enabling:
- **Targeted Marketing:** Personalized campaigns that improved engagement potential.  
- **Inventory Optimization:** Better stock allocation and reduced overstocking.  
- **Customer Retention:** Insights to design tiered loyalty programs aligned with customer value.

This project laid the foundation for further analytics initiatives such as **predictive modeling** (e.g., churn prediction) and **customer lifetime value estimation**.

---

## 🧰 Tools and Technologies Used
- **Python**  
- **Pandas**, **NumPy**  
- **Matplotlib**, **Seaborn**  
- **Scikit-learn**  
- **Jupyter Notebook**

---

## 🧠 Key Learning
This project strengthened my skills in **unsupervised learning**, **data preprocessing**, and **cluster analysis**. It also demonstrated how **machine learning** can bridge the gap between **data science and business strategy**, transforming raw data into actionable insights that drive growth and operational excellence.

---

## 🏁 Conclusion
Through this project, I successfully developed and deployed a **K-Means clustering model** to segment UrbanCart’s customers into four distinct, actionable groups.  
The insights derived empowered the company to personalize its marketing efforts, improve inventory management, and enhance customer loyalty — aligning perfectly with its mission to deliver **tailored shopping experiences through data-driven innovation**.

---

## 📂 Repository Structure
📦 UrbanCart-Customer-Segmentation
┣ 📜 README.md
┣ 📓 Case study - Unsupervised Learning (Clustering).ipynb
┣ 📊 data/
┣ 📈 visualizations/
┗ 📁 models/
