# SpaceX Falcon 9 – Exploratory Data Analysis

This repository contains the **Exploratory Data Analysis (EDA)** stage of the IBM Data Science Capstone Project.

The notebook explores historical SpaceX Falcon 9 launch data to understand which factors influence successful first-stage landings. Using Python visualization libraries, we analyze relationships between mission variables and identify trends that will later be used for predictive modeling.

---

# Learning Objectives

After completing this notebook, you will be able to:

- Explore a real-world launch dataset using Python.
- Create meaningful visualizations with Matplotlib and Seaborn.
- Analyze relationships between mission variables.
- Identify patterns associated with successful Falcon 9 landings.
- Interpret visual results and draw data-driven conclusions.
- Prepare the dataset for machine learning.

---

# Project Overview

The exploratory analysis investigates how different launch characteristics affect landing success.

The notebook answers questions such as:

- Does payload mass affect landing success?
- Which launch sites have the highest success rate?
- Which orbit types are associated with successful landings?
- How has Falcon 9 performance changed over time?
- Which variables appear to be the most informative for prediction?

---

# Dataset

The notebook uses the cleaned Falcon 9 launch dataset produced during the previous Data Wrangling stage.

Example features include:

- Flight Number
- Launch Site
- Booster Version
- Payload Mass (kg)
- Orbit Type
- Launch Year
- Landing Outcome

---

# Exploratory Analysis Workflow

```text
Load Dataset
      │
      ▼
Inspect Variables
      │
      ▼
Create Visualizations
      │
      ▼
Identify Patterns
      │
      ▼
Interpret Results
      │
      ▼
Prepare for Machine Learning
```

---

# Visualizations Included

The notebook contains several exploratory analyses, including:

### Launch Site Analysis

- Flight Number vs Launch Site
- Payload Mass vs Launch Site
- Launch Success by Launch Site

### Orbit Analysis

- Orbit Type vs Landing Success
- Flight Number vs Orbit Type
- Payload Mass vs Orbit Type

### Time Analysis

- Launch Success Trend by Year

Each visualization is followed by observations explaining the patterns identified in the data.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Repository Structure

```text
.
├── jupyter-labs-eda-visualization.ipynb
└── README.md
```

---

# How to Run

1. Clone the repository.

```bash
git clone https://github.com/AlionaVat/spacex-eda-visualization.git
```

2. Install the required packages.

```bash
pip install pandas matplotlib seaborn numpy
```

3. Open the notebook.

```bash
jupyter notebook
```

4. Run all notebook cells from top to bottom.

---

# Expected Learning Outcomes

By the end of this notebook, you should be able to:

- Perform Exploratory Data Analysis (EDA).
- Build effective statistical visualizations.
- Discover relationships between variables.
- Interpret analytical findings.
- Prepare a dataset for predictive modeling.

---

# Related Capstone Modules

This notebook is one part of the complete SpaceX Falcon 9 Capstone Project:

- Data Collection (API)
- Web Scraping
- Data Wrangling
- **Exploratory Data Analysis** ← current repository
- SQL Analysis
- Interactive Visual Analytics
- Predictive Modeling

---

# Author

**Aliona Vataman**

IBM Data Science Professional Certificate

