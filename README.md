## **Overview**

This project is the MSBA Capstone focused on analyzing private label opportunities using Numerator data. The analysis explores market basket trends, recommendation systems, and time series forecasting to identify growth opportunities for private label products across various demographic segments.

## **Table of Contents**

1. [Project Structure](#project-structure)  
2. [Key Features](#key-features)  
3. [Data Sources](#data-sources)  
4. [How to Run the Project](#how-to-run-the-project)  
5. [Results](#results)  
6. [Technologies Used](#technologies-used)  
7. [Contributors](#contributors)  

---

## **Project Structure**

```bash
Capstone/
├── Analysis/
│   ├── Market Basket/
│   │   ├── 02_Market_Basket_Analysis.ipynb
│   │   ├── 03_MBA_Retailer_Comparison.ipynb
│   │   └── Market_Basket.xlsx
│   ├── Recommendation Product Engine/
│   │   └── Product for Numerator 11.30.ipynb
│   └── Time Series/
│       ├── Beefsalesbyregionusda.xlsx
│       └── West USDA Beef Timeseries.R
├── Deliverables/
│   ├── Numerator UI App/
│   │   ├── 3_most_opportunistic_age_bucket.csv
│   │   ├── 3_most_opportunistic_ethnicity.csv
│   │   ├── 3_most_opportunistic_region.csv
│   │   ├── Benchmark_Comparison_Gap.csv
│   │   ├── age_bucket_chart.csv
│   │   ├── ethnicity_chart.csv
│   │   ├── census_region_chart.csv
│   │   ├── income_bucket_chart.csv
│   │   ├── numerator_ui.py
│   │   └── README.md
└── README.md
```

---

## **Key Features**

- **Market Basket Analysis (MBA):**  
  Identified product association rules and cross-selling opportunities for private label products.

- **Recommendation Product Engine:**  
  Developed a product recommendation system to enhance private label product visibility.

- **Time Series Analysis:**  
  Conducted forecasting on USDA beef sales data to understand seasonal and regional trends.

- **Interactive UI:**  
  Built a simple UI to visualize demographic opportunities across age, ethnicity, and income segments.

---

## **Data Sources**

- **Numerator Data:** Consumer purchasing data focusing on private label products.  
- **USDA Beef Sales Data:** Regional time series data for market trend analysis.  
- **Demographic Segments:** Age, ethnicity, income, and region-based CSV datasets.

---

## **How to Run the Project**

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/numerator-private-label-analysis.git
cd numerator-private-label-analysis
```

### **2. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3. Run the Jupyter Notebooks**
Navigate to the relevant folders and open notebooks for Market Basket Analysis, Recommendation Engine, or Time Series Analysis.

### **4. Launch the UI App**
```bash
python numerator_ui.py
```

---

## **Results**

- Identified key demographic groups with the highest growth potential for private label products.  
- Discovered cross-category purchase patterns that inform private label product placement.  
- Generated product recommendations tailored to consumer purchasing behavior.  

---

## **Technologies Used**

- **Languages:** Python, R  
- **Libraries:** Pandas, Scikit-learn, Matplotlib, Seaborn, Association Rules (MLxtend), Shiny (for R)  
- **Tools:** Jupyter Notebook, Excel, Power BI  

---

## **Contributors**

- **Miguel Garcia** – Data Analyst | MSBA Candidate, Class of 2025  
  [GitHub](https://github.com/mgarcia2895) | [LinkedIn](www.linkedin.com/in/miguel-garcia-887030155/)  

---

## **License**

This project is for academic and educational purposes only.
