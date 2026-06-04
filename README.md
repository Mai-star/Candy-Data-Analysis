# 🍬 Halloween Candy Hierarchy Analysis

### 📊 Project Overview
This project analyzes the **Halloween Candy Hierarchy 2017** dataset, a famous survey that captures people's sentiments (Joy, Despair, or Meh) toward various types of candy. The analysis explores gender-based preferences, age demographics, and the ultimate "power ranking" of candies.

---

### 📂 Dataset Source
The data is based on the **Science Creative Quarterly's** annual survey, available on **Kaggle**:
🔗 [Halloween Candy Hierarchy Dataset](https://www.kaggle.com/datasets/seifmohmed/candy-data)

---

### 🛠️ Key Files
- **`candy-data-visualization.ipynb`**: The Jupyter Notebook containing the full data pipeline (Cleaning -> EDA -> Visualization).
- **`candy_hierarchy_2017.xlsx`**: The original survey data in Excel format.

---

### 🔍 Key Findings & Insights
Based on the analysis of **2,400+** survey responses:

#### 1. Demographics & Distribution
**59%** of respondents were **Male**, while **35%** were **Female**, with the majority of participants being in their **30s and 40s**.
![Histogram of Candy Attributes](Candy-Data-Analysis/Histogram.png)

#### 2. The "Power Ranking"
Full-sized candy bars and Reese's Peanut Butter Cups consistently ranked highest in the "Joy" category, while items like "Anonymous brown globs" received the highest "Despair" ratings.
![Bar Graph of Popular Candy Types](Candy-Data-Analysis/Bar-Graph.png)
![Barh Graph of Candy Features](Candy-Data-Analysis/Barh-Graph.png)

#### 3. Consumer Behavior
Explored specific preferences, such as how people would prefer to donate candy, providing insights into consumer behavior.
![Pie Chart of Candy Donation Preferences](Candy-Data-Analysis/Donate-Pie-Chart.png)
![Pie Chart of Overall Candy Type Distribution](Candy-Data-Analysis/Pie-Chart.png)

---

### 💡 Conclusion
The 2017 Candy Hierarchy reveals that brand-name chocolate remains the undisputed king of Halloween, while non-candy items or generic sweets are met with overwhelming "Despair." This project demonstrates the ability to handle high-dimensional survey data with over **120 columns** and extract clear, humorous, and data-driven conclusions.

---

### 🛠️ Tech Stack
- **Python** (Pandas, NumPy)
- **Seaborn & Matplotlib** (Advanced Visualization)
- **Openpyxl** (Excel Data Handling)
