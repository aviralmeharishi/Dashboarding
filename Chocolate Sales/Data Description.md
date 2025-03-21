## 📂 Dataset Description: Chocolate Sales Data

### 📊 Overview
This dataset contains **1,094 records** and **6 columns**, detailing chocolate sales across different countries, salespersons, and products. It provides insights into revenue, shipment volumes, and sales trends.

### 🔍 Data Dictionary

| Column Name       | Data Type | Description |
|-------------------|----------|-------------|
| **Sales Person**  | String   | Name of the salesperson responsible for the sale. |
| **Country**       | String   | The country where the sale was made. |
| **Product**       | String   | The type of chocolate product sold. |
| **Date**         | String   | The date when the sale occurred (Format: `DD-MMM-YY`). |
| **Amount**       | String   | The total sales amount for the transaction (in dollars, requires cleaning). |
| **Boxes Shipped** | Integer  | Number of chocolate boxes shipped for the order. |

### 🔹 Sample Data

| Sales Person     | Country  | Product                | Date       | Amount   | Boxes Shipped |
|-----------------|---------|------------------------|-----------|---------|---------------|
| Jehu Rudeforth  | UK      | Mint Chip Choco        | 04-Jan-22 | $5,320  | 180           |
| Van Tuxwell     | India   | 85% Dark Bars         | 01-Aug-22 | $7,896  | 94            |
| Gigi Bohling    | India   | Peanut Butter Cubes   | 07-Jul-22 | $4,501  | 91            |
| Jan Morforth    | Australia | Peanut Butter Cubes | 27-Apr-22 | $12,726 | 342           |
| Jehu Rudeforth  | UK      | Peanut Butter Cubes   | 24-Feb-22 | $13,685 | 184           |

### 🛠️ Data Cleaning & Processing Notes:
- The `Amount` column has **currency symbols and commas** (e.g., `$5,320`), which need to be cleaned for numerical analysis.
- The `Date` column is stored as a **string** and should be converted to a **datetime format** for time-series analysis.

---

📌 **Use this dataset for analyzing sales trends, country-wise performance, and product demand!** 🚀
