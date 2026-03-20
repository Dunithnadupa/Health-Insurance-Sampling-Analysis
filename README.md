# 📊 Health Insurance Data Analysis using Sampling Techniques

## 🔍 Overview
This project presents a comparative analysis of different **survey sampling techniques** using the US Health Insurance Dataset (1,338 observations).  

The objective is to evaluate the effectiveness of sampling methods in estimating key population parameters such as **mean, total, and proportions** of medical insurance charges.

---

## 📁 Dataset Description
The dataset includes demographic and health-related variables:

- Age  
- Sex  
- BMI (Body Mass Index)  
- Number of Children  
- Smoker Status  
- Region (Northeast, Northwest, Southeast, Southwest)  
- Insurance Charges  

---

## ⚙️ Sampling Techniques Implemented

### 1. Simple Random Sampling (SRS)
- Equal probability for all individuals  
- Used as a baseline method  

### 2. Stratified Sampling
- Stratified by **smoker status**  
- Ensures representation of high-risk and low-risk groups  
- Improves estimation accuracy  

### 3. Two-Stage Cluster Sampling
- Clustered by **region**  
- Stage 1: Select clusters  
- Stage 2: Sample individuals within clusters  
- Useful for large-scale or geographically distributed populations  

---

## 📊 Key Analysis

- Sample size determination for each method  
- Estimation of:
  - Mean  
  - Total  
  - Proportions  
- Standard error comparison  
- Sampling weight calculations  
- Ratio estimation (Charges vs BMI)  
- Graphical analysis:
  - Histograms  
  - Boxplots  
  - Comparative visualizations  

---

## 📈 Key Findings

- ✅ **Stratified Sampling** produced the most accurate and stable estimates  
- ✅ Lowest standard errors observed in stratified design  
- ⚖️ **SRS** provided moderate accuracy with slight variability  
- ⚠️ **Cluster Sampling** showed higher variability due to cluster similarity  

### 💡 Insight:
- Smoking status has a **significant impact** on insurance charges  
- Regional differences have **less influence**  

---

## 🛠 Tools & Technologies

- **R Programming**
- Survey Package (`svydesign`, `svymean`, `svytotal`)
- Statistical Sampling Techniques
- Data Visualization

---

## 📌 Conclusion
Stratified Sampling was identified as the **most efficient and reliable method** for this dataset, demonstrating the importance of selecting appropriate sampling strategies for accurate statistical inference.

---

## 👨‍💻 Author
**R. Dunith Nadupa**  
Undergraduate in Statistics | Aspiring Data Analyst  

---

## 📎 References
- Dataset: https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset
