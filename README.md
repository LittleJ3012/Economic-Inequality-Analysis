*****Economic Inequality, GDP per Capita and Economic Freedom (Data Analysis Project)*****

***Project Overview***

This project investigates the **relationship between GDP per capita**, **economic inequality (Gini Index)**, and **economic freedom** across countries.

The analysis aims to explore:

* Whether richer countries tend to have lower or higher levels of economic inequality;
* How economic freedom (measured by the 2022 Freedom Index) correlates with GDP per capita and inequality;
* How different groups of countries compare in terms of inequality and economic freedom.

This project was developed as part of an independent academic study by **Computer Science student Julia Barcellos**,
**Federal University of Itajubá (UNIFEI), Minas Gerais – Brazil**.

---

**Dataset Description**

The project uses **three datasets**, stored inside the project folder:

**1. gini-coefficient.csv**

Contains historical Gini Index values for countries around the world.

Columns include:

* `country` — country name
* `year` — reference year
* `p0p100_gini_pretax` — pre-tax inequality coefficient



**2. gdp-per-capita-maddison-project-database.csv**

Income estimates from the Maddison Project Database.

Columns include:

* `country`
* `year`
* `gdp_pc` — GDP per capita (adjusted for purchasing power)


**3. index2022_data.csv**

Extracted from the **Heritage Foundation’s Economic Freedom Index (2022)**.

Columns include:

* `Country Name`
* `2022 Score`
* `World Rank`
* Sub-indexes (Fiscal Health, Government Size, Property Rights, etc.)


**Objectives of the Analysis**

The project focuses on three main goals:

** 1-Explore the evolution of inequality over time**

* Identify trends in Gini Index for selected countries
* Compare inequality between continents and political systems

**2-Evaluate the correlation between GDP per capita and inequality**

* Are richer countries more equal?
* Does higher GDP lead to reduced inequality?

**2-Investigate the relationship between economic freedom and both indicators**

* Do freer economies tend to be richer?
* Are they also more equal?
* How do the worst-ranked countries differ from the top-ranked ones?


##**Technologies Used**

The analysis was performed in Python using:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

Libraries/features included:

* **Pandas** → data cleaning & filtering
* **NumPy** → numerical handling
* **Matplotlib & Seaborn** → visualization
* **VS Code Jupyter Notebook** → interactive analysis


##**Main Visualizations**

The notebook includes:

* Line plots showing historical inequality
* Scatterplots comparing GDP vs. Gini
* Bar charts ranking countries by economic freedom
* Highlighted comparisons between selected countries


**Insights Expected**

Throughout the analysis, the project aims to examine:

* How inequality behaves in rich democracies vs. developing nations
* Whether economic freedom correlates positively with prosperity
* Identification of outlier countries with unusual patterns
* General tendencies linking institutional quality and inequality

---

**How to Run the Project**

1. Clone or download the repository
2. Install required libraries if necessary [matplotlib, numpy, pandas, seaborn]


This project was developed by Julia Barcellos, an undergraduate Computer Science student from the Federal University of Itajubá – UNIFEI, Brazil



