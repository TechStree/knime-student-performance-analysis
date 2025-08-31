# Student Performance Analysis using KNIME

A data warehousing and mining project that analyzes a simulated student dataset to uncover trends in academic performance. This project demonstrates a complete end-to-end data workflow, from data creation and manipulation to final visualization.

![final-chart.png](final-chart.png)

## 🎯 Objective
The goal was to simulate three related student datasets (Profiles, Academics, and Attendance) and perform core data manipulation tasks—filtering, grouping, and joining—to generate meaningful summaries and answer key questions about student performance.

## 🛠️ Tools Used
* **KNIME Analytics Platform:** Used for the entire data workflow, including data creation, transformation, and visualization.

## ⚙️ Project Workflow
1.  **Data Simulation:** Three distinct datasets were created directly in KNIME using the `Table Creator` node.
2.  **Data Filtering:** The `Row Filter` node was used to isolate specific records, such as students with marks below 40, to identify underperformers.
3.  **Data Aggregation:** The `GroupBy` node was used to calculate aggregate statistics, such as the average marks for each class and subject.
4.  **Data Joining:** The datasets were merged into a single, comprehensive table using the `Joiner` node based on a common `Student ID`.
5.  **Data Visualization:** A `Bar Chart` was created to visually compare the average academic performance across different classes.

## ✨ Key Skills Demonstrated
* ETL (Extract, Transform, Load)
* Data Cleaning & Manipulation
* Data Aggregation & Summarization
* Data Visualization
* Workflow Automation using KNIME
