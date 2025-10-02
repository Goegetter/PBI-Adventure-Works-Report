# Power BI Sales & Returns Report  

This repository contains a **Power BI Tabular Model Definition Language (TMDL)** representation of a Sales & Returns analysis report.  
The model defines a set of measures and calculations that provide insights into revenue, costs, orders, returns, and customer behavior.  

## 📊 Key Features  

The `Measure Table` includes reusable DAX measures such as:  

- **Sales & Returns Metrics**  
  - `Quantity Sold`, `Quantity Returned`, `Total Returns`, `Return Rate`  
  - `Bike Sales`, `Bike Returns`, `Bike Return Rate`  

- **Order Metrics**  
  - `Total Orders`, `Bulk Orders`, `Weekend Orders`  
  - `% of All Orders`, `High Ticket Orders`  
  - `Order Target`, `Order Target Gap`  

- **Customer Metrics**  
  - `Total Customers`  
  - `Avg Revenue per Customer`  
  - Customer detail measures (orders, revenue, full name)  

- **Revenue & Profitability**  
  - `Total Revenue`, `Total Cost`, `Total Profit`  
  - Rolling measures (`10-Day Rolling Revenue`, `90-Day Rolling Profit`)  
  - Month-to-month comparisons (`Prev Month Revenue`, `Prev Month Profit`, etc.)  
  - Target vs. Actual Gaps (`Revenue Target`, `Profit Target`, `Order Revenue Gap`)  

- **Price Adjustments**  
  - `Adjusted Price`, `Adjusted Revenue`, `Adjusted Profit`  
  - Comparison with overall and filtered average retail price  

These measures can be visualized in Power BI reports and dashboards to track **sales performance, profitability trends, and return rates**.  

## 🚀 Usage  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-org/pbi-sales-report.git

## 📜 License

This project is licensed under the MIT License – see the LICENSE
 file for details.


