# 🦉 Biodiversity Analysis in U.S. National Parks

## 📌 Project Overview
This project analyzes biodiversity in four U.S. national parks using data science techniques. By exploring species distribution, conservation status, and observational trends, we aim to derive insights into the state of wildlife and highlight species at risk.

## 🎯 Project Goals
- Understand the biodiversity composition across national parks.
- Identify species that are endangered, threatened, or in recovery.
- Analyze the correlation between the number of species observations and their conservation status.

## 📊 Dataset Information
We use two datasets:
1. **observations.csv** – Contains records of species observations in different parks.
2. **species_info.csv** – Provides species classification and conservation status.

Both datasets are merged based on the **scientific_name** column, and missing values in conservation status are filled with "not listed."

## 🛠️ Tools & Libraries
- **pandas**: Data manipulation and cleaning.
- **numpy**: Numerical operations.
- **matplotlib & seaborn**: Data visualization.
- **scipy.stats**: Statistical correlation analysis.

## 📌 Key Insights & Findings
### 🔹 Biodiversity Distribution
- The dataset includes **25,632** observations across **7 species categories**.
- **Vascular plants** are the most abundant category, while **reptiles** and **amphibians** are the least observed.

### 🔹 Conservation Status Breakdown
| Status                | Count |
|----------------------|-------|
| Species of Concern   | 732   |
| Endangered          | 80    |
| Threatened          | 44    |
| In Recovery         | 24    |

### 🔹 Most Endangered Species
Top 10 species with the highest recorded risk:
```
Canis lupus                     1430
Etheostoma percnurum             166
Geum radiatum                    162
Myotis grisescens                160
Gymnogyps californianus          156
Glaucomys sabrinus coloratus     153
Ovis canadensis sierrae          153
Chasmistes liorus                146
Picoides borealis                146
Myotis sodalis                   145
```

### 🔹 Biodiversity Comparison Across Parks
- Each park has a nearly equal distribution of endangered species.
- Species variety and conservation needs vary across locations.

### 🔹 Correlation Analysis
- **Pearson correlation coefficient** between species observations and conservation status: **-0.090**.
- The negative correlation suggests that endangered species tend to have fewer recorded observations.

## 📌 Project Workflow
1. Load and inspect data.
2. Merge datasets and handle missing values.
3. Conduct exploratory data analysis (EDA).
4. Visualize biodiversity trends and conservation status.
5. Perform statistical correlation analysis.
6. Summarize insights and conclusions.

## 📈 Visualizations
- Bar charts showing species count per category.
- Distribution of conservation statuses across parks.
- Top 10 most endangered species.
- Scatter plot of species observations vs. conservation status.

## 📌 Conclusions
- Most species are not listed under conservation status, but those that are listed need monitoring.
- National parks play a crucial role in protecting biodiversity, yet endangered species are observed less frequently.
- Further research could explore external factors like climate impact or human activity on endangered species.

## 🚀 Future Improvements
- Incorporate additional datasets (e.g., climate, habitat changes).
- Perform predictive modeling on species extinction risks.
- Build an interactive dashboard for biodiversity monitoring.

## 💡 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/biodiversity-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to explore the analysis.

## 📌 About
*This project is part of my portfolio in Data Science, showcasing my skills in data analysis, visualization, and statistical insights.*

---
📩 *For questions or collaborations, feel free to reach out!*

