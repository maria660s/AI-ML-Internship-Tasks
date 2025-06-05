# 📊 Iris Dataset Exploration and Visualization

## 📝 Task Overview

**Task 1: Exploring and Visualizing a Simple Dataset**

This project involves loading, inspecting, and visualizing the Iris dataset to understand data trends and distributions. The goal is to practice data exploration skills using Python libraries such as `pandas`, `matplotlib`, and `seaborn`.

---

## 🎯 Objective

- Load the Iris dataset from a CSV file.
- Perform basic data inspection and descriptive statistics.
- Visualize relationships, distributions, and outliers using different plots.

---

## 📁 Dataset

- **Name:** Iris Dataset
- **Format:** CSV
- **Description:** A classic dataset containing measurements for 150 iris flowers from three different species (Setosa, Versicolor, Virginica). Features include:
  - sepal_length
  - sepal_width
  - petal_length
  - petal_width
  - species (target label)

---

## 🛠️ Tools and Libraries Used

- Python 3.x
- [Pandas](https://pandas.pydata.org/) – for data loading and inspection
- [Seaborn](https://seaborn.pydata.org/) – for advanced data visualization
- [Matplotlib](https://matplotlib.org/) – for plotting

---

## 🔍 What the Code Does

1. **Data Loading**
   - Loads `iris.csv` using `pandas.read_csv()`.

2. **Data Inspection**
   - Prints dataset shape, column names, and first few rows using `.head()`.
   - Displays info with `.info()` and descriptive statistics using `.describe()`.

3. **Visualization**
   - **Scatter Plot:** Visualizes relationships between sepal and petal features.
   - **Histograms:** Shows value distributions of each numerical feature.
   - **Box Plots:** Identifies outliers by plotting distributions per species.

---

## ▶️ How to Run

1. Clone or download this repository.
2. Ensure `iris.csv` is in the same folder as the script or notebook.
3. Run the Python script or Jupyter Notebook.

Example (if using a script):
```bash
python iris_visualization.py
