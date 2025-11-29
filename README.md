# 📊 Interactive Data Visualizations with Plotly – Beginner Practice Project

This project contains a collection of Plotly charts I created while learning data visualization in Python as part of my IBM Data Analyst Professional Certificate course.

It is designed to help beginners understand how to create and explain interactive visualizations step-by-step.

---

## 🚀 Charts Included

| Chart Type | What It Shows | What I Learned |
|-----------|---------------|----------------|
| Scatter Plot | Age vs Income | Relationship between variables, tooltips |
| Line Chart | Monthly Bicycle Sales | Trends across months |
| Histogram | Height Distribution | Frequency and probability spread |
| Bubble Chart | Crimes by City | Size encoding, grouping effects |
| Pie Chart | Family Expenses | Part-to-whole comparison |
| Sunburst Chart | Family Hierarchy | Hierarchical relationships |

---

## 🛠️ Tools Used

- Python
- Plotly Express & Graph Objects
- NumPy
- Jupyter Notebook (Anaconda)

---

## 📚 Learning Outcomes

✔ Difference between axes-based charts & part-to-whole charts  
✔ Using `labels=`, `title=`, `size=`, `parents=` and interactive features  
✔ Understanding distributions and relationships in data  
✔ Improved confidence in interpreting tooltips and chart insights  

---

## 📝 Sample Code – Scatter Plot

```python
import plotly.express as px

fig = px.scatter(
    x=age_array,
    y=income_array,
    title="Income vs Age",
    labels={"x": "Age (Years)", "y": "Income"}
)

fig.show()
__________________________________________
🙋‍♀️ Author

👤 Vidya V.G
📍 Scotland, UK
🎯 Aspiring Data Analyst
🚀 Exploring Data Visualization & Dashboards


