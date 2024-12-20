# 📊 Job Insights with Pivot Tables and Power BI Visualizations

This repository contains a detailed analysis of global job datasets, focusing on salaries, skills, and roles across different countries. By leveraging Power Query, Power Pivot, and DAX, I've created insightful visualizations to uncover trends and make data-driven decisions.

---

## 💡 Problem Statement

With globalization and the growing tech industry, understanding how job roles vary in salary and required skills across different countries is crucial. This analysis aims to answer questions like:

1. **How do median salaries in the USA compare to other countries for the same roles?**
2. **What are the top skills required for a specific role in a given country?**
3. **How do salaries vary based on specific skills, and how common are these skills?**
4. **Which roles demand the highest number of skills, and how do those roles pay?**

---

## 🛠️ How I Solved It

1. **Data Cleaning** – Using **Power Query** to thoroughly clean and prepare the dataset.
2. **Data Modeling** – Inserting the cleaned data into **Power Pivot** and establishing necessary relationships.
3. **DAX Measures** – Creating custom measures using **DAX** to enhance the analysis.
4. **Visualizations** – Building dynamic pivot tables and pivot charts with slicers for interactivity.

---

## 📊 Visualizations

### 1. 🌍 Median USA Salary vs. Selected Countries

- **Pivot Table**: Shows median salaries for job roles in the USA and compares them with selected countries.
- **Pivot Chart**: A **Line Chart** with a **Country Slicer** to dynamically compare salaries.

#### 💡 Insight:
This visualization helps identify how each role's salary in the USA stacks up against other countries.

![Example Line Chart](#) <!-- Placeholder for image link -->

---

### 2. 📚 Top Skills Required by Role and Country

- **Pivot Table**: Counts the frequency of each skill by job title and country.
- **Pivot Chart**: A **Bar Chart** with **Country** and **Job Title Slicers**.

#### 💡 Insight:
Quickly identify the **top 10 skills** required for a specific role in a particular country.

![Example Bar Chart](#) <!-- Placeholder for image link -->

---

### 3. 💸 Median Salary by Skill

- **Pivot Table**: Calculates median salary for each skill.
- **Pivot Chart**: A **Combo Chart** (line and bar) showing:
  - Median salary by skill.
  - Job count for each skill.
- **Slicers**: Job Title and Country.

#### 💡 Insight:
Understand which skills are associated with higher salaries and how common those skills are.

![Example Combo Chart](#) <!-- Placeholder for image link -->

---

### 4. 👥 Skill Count vs. Salary

- **Pivot Table**: Analyzes the relationship between skills and salaries for different roles.
- **Pivot Chart**: A **Combo Chart** showing:
  - Median salary.
  - Average number of skills required per role.

#### 💡 Insight:
Explore how roles demanding more skills are compensated.

![Example Skill Comparison Chart](#) <!-- Placeholder for image link -->

---

## 🔄 Workflow

1. **Data Cleaning** in Power Query.
2. **Modeling** relationships in Power Pivot.
3. **Creating Measures** using DAX.
4. **Building Pivot Tables and Pivot Charts**.

---

## 👍 Why This Project is Useful

- **For Job Seekers**: Helps understand salary expectations and required skills by country.
- **For Recruiters**: Identifies competitive salaries and essential skills for various roles.
- **For Data Enthusiasts**: A practical example of leveraging Excel's powerful features (Power Query, Power Pivot, DAX).

---

## 📦 Files in This Repository

- **Dataset**: The cleaned job dataset.
- **Power BI / Excel File**: Contains all pivot tables, pivot charts, and DAX measures.
- **README.md**: This documentation.

---

## 📚 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/job-insights-analysis.git
   ```
2. Open the Excel file.
3. Explore the pivot charts and interact with slicers for dynamic insights.

---

## 🚀 Future Improvements

- Add more datasets for deeper analysis.
- Integrate with Power BI for advanced visualization.

---

## 🌟 Acknowledgments

Special thanks to **Microsoft Excel** and **Power BI** communities for their resources and guidance!

---

### 👋 Let's Connect!

- **LinkedIn**: https://www.linkedin.com/in/moparthybharghavameghamsh/

Feel free to open an issue or contribute! 🚀
