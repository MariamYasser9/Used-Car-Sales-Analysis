# Used-Car-Sales-Analysis

## 📘 Overview
This project explores a **Used Car Sales Dataset** to uncover pricing patterns, manufacturer performance, car characteristics, and sales trends over time.

The analysis was conducted using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**, focusing on key business insights that can help understand the used car market better.

---

## 🧩 Dataset Information
**Source:** [Kaggle - Used Car Sales Dataset](https://www.kaggle.com/datasets/sandeep1080/used-car-sales)  
**Rows:** 10000  
**Columns:** 25  

**Main Features:**
- Car specifications: `Car Name`, `Manufacturer Name`, `Car Type`, `Gearbox`, `Engine Power-HP`
- Pricing: `Price-$`, `Purchased Price-$`, `Sold Price-$`, `Margin-%`
- Dates: `Manufactured Year`, `Purchased Date`, `Sold Date`, `Sold Year`
- Sales info: `Sales Agent Name`, `Car Sale Status`, `Sales Rating`, `Feedback`

---

## 🧹 Data Cleaning & Preparation
- Removed duplicates and null/invalid entries  
- Created derived feature: **Car Age = 2024 - Manufactured Year**  
- Handled placeholder year `1970` (indicating unsold cars)  
- Removed extreme outliers from `Price-$` and `Purchased Price-$`  
- Converted dates to datetime format and extracted year  

---

## 📊 Visualizations & Insights
Below are some of the key visualizations created:

| Visualization | Description / Insight |
|---------------|------------------------|
| 💵 **Price Distribution** | Most cars are priced between \$10K–\$25K — middle-market dominance |
| 🏷️ **Purchased Price Distribution** | Identified price outliers and normalized range |
| ⏳ **Price vs Car Age** | Older cars tend to have significantly lower prices |
| 🛞 **Price vs Mileage** | Negative correlation between mileage and price |
| 🏭 **Median Price by Manufacturer** | Certain brands maintain higher resale values |
| 🚙 **Price by Car Type** | SUVs and premium cars show higher median prices |
| ⚙️ **Gearbox vs Price** | Automatic cars are generally more expensive |
| 🔥 **Top 10 Sold Car Models** | Highlights the most demanded models |
| 📈 **Number of Cars Sold Per Year** | Sales have fluctuated; unsold entries (1970) excluded |
| 🌡️ **Correlation Heatmap** | Shows strong relation between `Price-$`, `Purchased Price-$`, and `Margin-%` |

---

## 🪄 Tools & Libraries
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📈 Key Insights
- The **used car market** is mostly driven by mid-range prices.  
- **Car age and mileage** are the strongest indicators of price depreciation.  
- **Automatic transmission cars** generally sell for higher prices.  
- Certain **manufacturers consistently retain higher resale value**.  
- **Yearly sales analysis** shows variation possibly tied to supply & demand or external market factors.

---

## 🧠 Future Improvements
- Develop a **machine learning model** to predict car prices.  
- Build an **interactive dashboard** using Plotly or Power BI.  
- Incorporate **geographical insights** (if location data is detailed).  

---

## 🏁 Conclusion
This analysis provides a data-driven view of used car sales, helping understand **pricing behavior**, **buyer trends**, and **market performance**.  
It can assist dealerships or resale platforms in optimizing their pricing and sales strategies.

---

## 🙌 Acknowledgments
Special thanks to my instructors and mentors for their continuous guidance throughout this project.  
Part of the **DEPI Scholarship Program** learning journey.

---

### 📂 Project Structure
├── Used_Car_analysis.ipynb # Jupyter notebook with full analysis
├── used_car_sales.csv # Dataset
├── README.md # Project documentation
└── visuals/ # Optional folder for exported plots

---

### 📬 Connect with Me
If you’d like to discuss this project or collaborate:

- 💼 [LinkedIn](https://www.linkedin.com/in/mariam-yasser1-/)
