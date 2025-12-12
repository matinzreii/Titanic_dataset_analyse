# Titanic Data Visualization & Analysis 🚢

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python. It visualizes passenger demographics and class distributions to uncover patterns related to gender and ticket class.

## 📋 Overview

The script processes the `titanic.csv` file to:
1. **Clean Data**: Removes unnecessary columns (`deck`, `who`, `adult_male`, `parch`, `sibsp`).
2. **Analyze Statistics**: displays basic info, descriptive statistics, and null values.
3. **Visualize Distribution**:
   - Overall gender distribution.
   - Gender distribution across different ticket classes.
   - Separate class analysis for Male and Female passengers.

## 🛠️ Libraries Used

- **Pandas**: For data manipulation and cleaning.
- **Matplotlib**: For displaying charts.
- **Seaborn**: For statistical data visualization (Countplots).
- **NumPy**: For numerical operations.

## 🚀 How to Run

1. Make sure you have `titanic.csv` in the project directory.
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn numpy
