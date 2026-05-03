# Effectiveness Analysis of Electronic Monitoring (EM) System
> **Comparative Analysis of Recidivism Prevention Effectiveness by Crime Type**

---

## 🔍 Project Overview
This project provides a data-driven evaluation of the **Electronic Monitoring (EM) system** to determine its effectiveness in preventing recidivism. By analyzing various offense categories, this research identifies which crime types show the highest and lowest deterrence levels under electronic supervision, aiming to provide insights for optimized policy-making.

## 🔬 Research Background
I conducted this analysis to explore the intersection of **data science and public safety**. The study focuses on whether the uniform application of the EM system is equally effective across different criminal behaviors or if a more tailored approach is required.

## 🛠 Tech Stack & Methodology
*   **Language**: `Python 3.x`
*   **Environment**: `Jupyter Lab`
*   **Libraries**: 
    *   `Pandas` / `NumPy`: For data preprocessing and cleaning.
    *   `Matplotlib` / `Seaborn`: For visualizing crime trends and effectiveness rates.
*   **Key Approach**: 
    *   Exploratory Data Analysis (EDA) on recidivism rates.
    *   Comparative statistical testing across crime types (e.g., sex offenses, homicide, robbery, and abduct).
      
## 📈 Key Insights & Findings
Based on the statistical analysis of the dataset, several key insights were identified:

### 1. Effectiveness by Crime Type
*   **High Deterrence**: Certain offense categories (Homicide, Robbery) showed a significant decrease in recidivism rates after the implementation of Electronic Monitoring.
*   **Low Deterrence**: In contrast, the deterrent effect was relatively lower for sex offenses and abduct crimes, suggesting that EM alone may not be sufficient for crimes driven by economic motives.

### 2. Conclusion for Policy-Making
*   The results highlight that a "one-size-fits-all" approach to electronic monitoring is insufficient. 
*   Strategic differentiation is required: while the current system works well for homicide and robbery, sex offense prevention and abduct requires a fundamental shift in strategy, potentially incorporating behavioral analysis or more intensive psychological interventions alongside technology.

## 📂 Project Structure
```text
.
├── Data_Analysis.ipynb         # Main analysis notebook (Data Preporcessing, EDA, Visualization)
├── data/                       # Dataset (Recidivism rates & EM statistics)
├── Report/                     # Visualization results and insights
└── README.md                   # Project documentation
