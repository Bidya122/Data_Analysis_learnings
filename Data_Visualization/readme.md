Learning data visualization in Python using pandas, numpy, matplotlib, seaborn, plotly, and 3D plotting: covering histograms, box/violin plots, count/bar plots, scatter/pair plots, heatmaps, pie charts, and error bar plots with clear use-cases.

📚 Libraries used: 

- pandas (pd) → handle datasets (tables, rows/columns)

- numpy (np) → generate numbers, random data, math functions

- matplotlib.pyplot (plt) → base plotting (bar, line, scatter, pie, customization)

- seaborn (sns) → high-level, prettier statistical plots

- plotly.express (px) → interactive plots

- mpl_toolkits.mplot3d → 3D plotting support in matplotlib

# 📊 Data Visualization Cheat Sheet (Seaborn & Matplotlib)

| Plot                  | Function               | When to Use                                           | How to Remember (1-liner) |
|-----------------------|------------------------|------------------------------------------------------|---------------------------|
| 📦 **Box plot**       | `sns.boxplot`          | Compare distribution, median, outliers across groups | "Box shows median & spread, whiskers show extremes" |
| 🎻 **Violin plot**    | `sns.violinplot`       | Like boxplot but also shows distribution shape (density) | "Boxplot + distribution = violin" |
| 📉 **Histogram**      | `sns.histplot`         | Distribution of one numeric variable                 | "Bins of values" |
| 📊 **Count plot**     | `sns.countplot`        | Count of categories (frequency)                      | "Barplot but counts automatically" |
| 🟦 **Bar plot**       | `sns.barplot`          | Average of numeric values per category               | "Bar shows mean (not counts)" |
| 🔵 **Scatter plot**   | `sns.scatterplot`      | Relationship between two numeric variables           | "Dots show x–y relationship" |
| 🔗 **Pair plot**      | `sns.pairplot`         | Relationships between all numeric columns            | "Matrix of scatterplots" |
| 🔥 **Heatmap**        | `sns.heatmap`          | Show numeric values in a grid (matrix) with color    | "Color = value" |
| 🥧 **Pie chart**      | `plt.pie`              | Show percentage of a whole                           | "Circle slices = proportion" |
| 📈 **Line plot w/ error bars** | `sns.pointplot` | Compare means across categories, with variability (SD/CI) | "Points + line + error bars" |
| ⚪ **3D scatter plot** | `Axes3D + ax.scatter` | Show relation between 3 variables at once            | "Dots in 3D space" |
