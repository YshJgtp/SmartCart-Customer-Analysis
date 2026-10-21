# SmartCart Customer Analysis

## Project Overview
This repository contains the `smartcart.csv` dataset and a starter Jupyter Notebook for exploring customer demographics, purchasing behavior, shopping channels, and campaign response.

> **Note:** The uploaded `Problem statements.pdf` could not be read as searchable text, so this README describes the project based on the dataset columns. Update the project objective after confirming the exact problem statement.

## Dataset
- **File:** `data/smartcart.csv`
- **Rows:** 2,240
- **Columns:** 22
- **Target-like field:** `Response` (0/1), which may represent response to a campaign; confirm this interpretation against the original dataset documentation.

Some fields include:
- Customer profile: `Year_Birth`, `Education`, `Marital_Status`, `Income`
- Household: `Kidhome`, `Teenhome`
- Purchase amounts: `MntWines`, `MntFruits`, `MntMeatProducts`, `MntFishProducts`, `MntSweetProducts`, `MntGoldProds`
- Shopping channels: `NumWebPurchases`, `NumCatalogPurchases`, `NumStorePurchases`
- Engagement: `Recency`, `NumDealsPurchases`, `NumWebVisitsMonth`, `Complain`, `Response`

## Repository Structure
```text
SmartCart-Customer-Analysis/
├── data/
│   └── smartcart.csv
├── notebooks/
│   └── SmartCart_Exploratory_Analysis.ipynb
├── Problem statements.pdf
├── requirements.txt
├── .gitignore
└── README.md
```

## Getting Started
1. Install Python 3.10 or later.
2. Create and activate a virtual environment (recommended).
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Open the notebook:

   ```bash
   jupyter notebook
   ```

5. Open `notebooks/SmartCart_Exploratory_Analysis.ipynb` and run the cells from top to bottom.

## Initial Analysis Questions
- What are the distributions of customer income and age?
- Which product categories generate the highest spending?
- Which shopping channel is used most frequently?
- How does purchase behavior vary by education or marital status?
- Which customer characteristics are associated with `Response`?

## Next Steps
- Confirm the exact objective in the problem statement.
- Handle missing values and validate data types.
- Check duplicates and outliers.
- Visualize customer and purchasing patterns.
- If prediction is required, split data into training/test sets and evaluate a suitable baseline model.

## License
Add a license before public reuse if you own or have permission to redistribute all included materials.
