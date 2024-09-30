---
layout: post
title: "Using Jupyter Notebooks with GitHub Pages"
date: 2024-01-01
---

## About Me
Hi, I'm Tom, a data analyst student in London. I'm learning data visualisation and analysis, with a focus on presenting insights clearly and effectively. This notebook showcases my ability to work with Python libraries like Pandas and Matplotlib.

**Education**: MBA
**Skills**: Data Visualization, Python, Machine Learning


```
# Importing necessary libraries
import pandas as pd
import matplotlib.pyplot as plt
```


```
# Creating a dataset
data = {'Category': ['A', 'B', 'C', 'D'],
        'Values': [23, 45, 12, 34]}

# Converting to DataFrame
df = pd.DataFrame(data)

# Display the data
df
```


```
# Visualizing the data
plt.figure(figsize=(8, 5))
plt.bar(df['Category'], df['Values'], color='skyblue')
plt.title('Sample Data Visualization')
plt.xlabel('Category')
plt.ylabel('Values')
plt.show()
```


