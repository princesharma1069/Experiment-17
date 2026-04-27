# Aim: Basic charts and visual encoding
## Theory:
This experiment focuses on Data Visualization, a critical component of data analysis used to transform complex datasets into visual representations like charts and graphs to uncover patterns, trends, and correlations.
By utilizing the matplotlib and seaborn libraries, the program demonstrates how to generate various plots—such as bar charts, histograms, and scatter plots—to interpret categorical and numerical distributions effectively.

Matplotlib:

The foundational, low-level plotting library for Python. It provides complete programmatic control over every element of a figure — axes, labels, colors, line styles, markers, and layout. It is built around the pyplot sub-module and can produce static, animated, and interactive figures.

import matplotlib.pyplot as plt: Imports the primary library used for creating static, interactive, and animated visualizations in Python.

Seaborn:

A statistical data visualization library built on top of Matplotlib. It provides a higher-level interface that produces polished, statistically informative plots with significantly less code. It integrates natively with Pandas DataFrames.

import seaborn as sns: Imports a high-level interface based on matplotlib for drawing attractive and informative statistical graphics.

Matplotlib offers more granular control (custom markers, colors, annotations via plt.text(), reference lines via plt.axvline(), grid via plt.grid()). Seaborn offers built-in statistical features (confidence intervals, KDE, automatic hue encoding) and requires less code for standard statistical plots.

Commands used:

plt.bar(): Creates a bar chart to compare different categories of data using rectangular bars.

plt.xlabel() / plt.ylabel(): Sets the text labels for the x-axis and y-axis respectively to provide context to the plot.

plt.title(): Adds a main heading to the top of the chart to describe the visualization.

plt.show(): Renders and displays all currently active figure objects onto the screen.

plt.hist(): Generates a histogram to represent the distribution of a continuous numerical variable by binning data.

plt.scatter(): Produces a scatter plot to observe the relationship or correlation between two numerical variables.

plt.pie(): Creates a pie chart to illustrate numerical proportions as slices of a circle.

plt.legend(): Places a box on the graph to describe the different elements or data series plotted.

sns.lineplot(): Draws a line graph to show data trends over a continuous interval or time period.

sns.countplot(): Uses bars to show the frequency of observations in each categorical bin.

sns.boxplot(): Displays the distribution of data based on a five-number summary (minimum, first quartile, median, third quartile, and maximum).

plt.text(x, y, s, ha, va):Places text string s at position (x, y) with specified horizontal (ha) and vertical (va) alignment.

plt.figure(figsize=(w,h)):Creates a new figure with specified width and height in inches.
## Conclusion:
Through this experiment, it is concluded that Data Visualization is essential for effective data storytelling. By selecting appropriate plots—such as bar charts for comparisons, histograms for distributions, and scatter plots for correlations—analysts can present data in an intuitive way that simplifies the decision-making process.
