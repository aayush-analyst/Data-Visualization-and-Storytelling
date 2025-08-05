# Global-Superstore-dashboard-Storytelling
Power BI dashboard analyzing Global Superstore sales, profit, and product trends.

##  Tools Used:
- Power BI
- Global Superstore Dataset

## First Page: Dashboard 

##  Key Metrics Displayed: 
"Card(new)" visual used to display this metrics.
- Total Sales: ₹12.8M
- Total Profit: ₹1.47M  
- Total Transactions: 51K  
- Average Delivery Days: 3.97

##  Visuals Included:
- Profit by Month : "Line chart" visual used to display this profit by month.
- Total Sales by Segment : "Donut chart" is used to display the percentage of each segment.
- Total Sales by Ship Mode : "Clustered bar chart" is used to show the ship mode. 
- Top 10 Products by Sales : "Clustered colmun chart" is used to show the top 10 products by sales using Top N filter 
- Total Sales by Country & City : "Filled Map" visual is used to display every country and city depend on the sales and putted the parameter.
- Interactive filters: Segment, Region, Ship Mode

##  Visual Storytelling:
- June and August are the most profitable months  
- Consumer segment generates the most sales (51%)  
- Standard Class is the most used shipping mode (₹7.6M sales)  
- Apple & Cisco products are top-sellers  
- Furniture category shows inconsistent profits — needs attention

## Dashboard Screenshot:
<img width="1543" height="862" alt="Intern first page" src="https://github.com/user-attachments/assets/77c8ef61-7f48-4fc9-acc0-2d10e16ed049" />


## Second Page: Comparison report

## Key Metrics Displayed:
"Card(new)" visual used to display this metrics.
- Total Sales: ₹12.8M
- Total Profit: ₹1.47M  
- Total Transactions: 51K 

##  Visuals Included:
- Sales vs Profit by sub-category: "Line chart" is used to display the comparison between sales and profit.
- Comparison of total sales last year:
  1. In this visual we have recorded the comparison of sales between last year sales and this year sales using DAX measures :-
     "Orders data last year = CALCULATE([Total Sales],SAMEPERIODLASTYEAR(Orders[Order Date].[Date]))"
  2. By using "Clustered column chart" we have recorded comparison of sales was their in last year and this year.
  3. Table format also show the comparison of sales quaterly between year and previous year. 
- Interactive filters:
  1. Year, Country, Category, Order Priority: "Slicer" are uesd to make the complete dashboard interactive and record the valuable insights.
  2. Month : "Button Slicer" is used to display month in grid form.


## Comparison reportScreenshot:
<img width="1550" height="862" alt="Second page" src="https://github.com/user-attachments/assets/419c3d1a-fbe5-4f81-bdfc-556d95494558" />





## Author
**Aayush Pardeshi**
---


