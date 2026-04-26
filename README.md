<img width="1919" height="1002" alt="Screenshot 2026-04-23 130923" src="https://github.com/user-attachments/assets/21c75659-fd1b-4e83-ae36-05fa6aeef5b2" />


<img width="1919" height="962" alt="Screenshot 2026-04-23 130943" src="https://github.com/user-attachments/assets/96e869b1-6d68-4354-9f08-6bef6222e37b" />


# 🚨 Homicide Data Analysis Dashboard

An interactive **Homicide Analysis Dashboard** built using Python and Panel to explore patterns across time, geography, weapon usage, relationships, and gender.

---

## 📌 Project Overview

This project focuses on transforming raw homicide data into meaningful insights through a complete data analysis pipeline:

> **Data Cleaning → Feature Engineering → Exploratory Analysis → Interactive Dashboard**

The final output is a **fully interactive dashboard** that allows users to explore crime patterns dynamically.

---

## 🎯 Objectives

- Clean and preprocess real-world crime data  
- Identify trends and patterns across multiple dimensions  
- Build interactive and user-friendly visualizations  
- Develop a structured dashboard using Panel  
- Enable dynamic filtering and real-time insights  

---

## 📂 Dataset

The dataset contains historical homicide records with features such as:

- Year, Month  
- State, City  
- Weapon used  
- Victim–Perpetrator relationship  
- Perpetrator gender  
- Incident counts  

---

## 🧹 Data Cleaning & Processing

Key preprocessing steps:

- Replaced `"Unknown"` values with proper handling  
- Converted columns to correct data types  
- Removed invalid and inconsistent entries  
- Created grouped features:
  - `Weapon_Group`
  - `Relationship_Group`
- Removed duplicates to ensure accurate incident counting  
- Filtered dataset (up to 2003) for reliable trend analysis  

---

## 📊 Exploratory Data Analysis

Key analyses performed:

- 📈 **Time Trend Analysis** – Crime variation across years  
- 🌍 **Geographical Analysis** – State-wise distribution  
- 🔫 **Weapon Distribution** – Dominance of weapon types  
- 👥 **Relationship Analysis** – Victim–perpetrator patterns  
- ⚧ **Gender vs Weapon** – Distribution across categories  
- 🔵 **Multi-variable Analysis** – Combined insights using bubble visualization  

---

## 📊 Dashboard Features

The dashboard is built using **Panel** and includes:

### 🔹 Interactive Filters
- Year range slider  
- State selection  
- Weapon group  
- Relationship group  
- Perpetrator gender  

---

### 🔹 Visualizations

- Multi-variable Bubble Chart (advanced analysis)  
- Trend Line Chart  
- State-wise Bar Chart  
- Weapon Distribution Donut Chart  
- Relationship Treemap  
- Gender vs Weapon Heatmap  

---

### 🎨 UI Design

- Dark theme dashboard  
- Neon-inspired color palette  
- Card-based layout with subtle glow effects  
- Consistent and responsive design  

---

## 🛠️ Tech Stack

- **Python**
- **Pandas & NumPy** (data processing)
- **Plotly & hvPlot** (visualizations)
- **Panel** (dashboard development)

---

## 📁 Project Structure

├── 01_data_cleaning.ipynb
├── 02_visualization.ipynb
├── dashboard.ipynb
├── cleaned_data.csv
├── README.md


---

## 🔍 Key Insights

- Crime incidents peaked in the early 1990s and declined afterward  
- Certain states contribute disproportionately to total incidents  
- Firearms are the most commonly used weapon  
- Crimes are more frequent among known individuals  
- Male perpetrators dominate across categories  

---

## ⚠️ Limitations

- Dataset limited to year 2003  
- Presence of "Unknown" values affects precision  
- Complex visualizations may require interpretation  

---

## 🚀 How to Run

```bash
# Install dependencies
pip install pandas numpy plotly hvplot panel

# Run the dashboard
panel serve dashboard.ipynb\
```
---

# Improve hosting documentation

## 📌 Final Note

This project demonstrates a complete pipeline from raw data to an interactive analytical dashboard, combining **data preprocessing, visualization, and UI design**.

---
