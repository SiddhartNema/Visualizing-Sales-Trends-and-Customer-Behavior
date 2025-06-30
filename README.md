# Visualizing-Sales-Trends-and-Customer-Behavior

This project performs data cleaning, aggregation, and visualization on a car dataset containing brand-wise details like price, mileage, power, safety, and rating.

## 📁 Dataset Columns
- Brand  
- Car Name  
- Price  
- Rating  
- Safety  
- Mileage  
- Power (BHP)  

## 🛠 Tools & Libraries Used
- Python (Pandas, NumPy)
- Data Visualization: Seaborn, Matplotlib, Plotly
- Jupyter Notebook

## ✅ Key Tasks Performed
- Cleaned complex string-based fields (like `Price`, `Mileage`, `Power (BHP)`)
- Aggregated brand-level performance using `groupby()` and `mean()`
- Created visual insights using:
  - 📊 Barplot (Price by Brand)
  - 📈 Lineplot (Trends)
  - 🔥 Heatmap (Correlations)
  - 🌐 Interactive plots with Plotly


## 📌 How to Run
1. Clone the repository  
2. Open `car_analysis.ipynb` in Jupyter Notebook  
3. Install required libraries (see below)  
4. Run all cells  

```bash
pip install pandas matplotlib seaborn plotly
