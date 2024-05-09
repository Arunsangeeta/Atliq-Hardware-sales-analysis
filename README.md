
<p4>Atliq-Hardware-Business analysis</p4><br>
To check live project please refer my novyproportfolio here-> https://www.novypro.com/profile_about/sangeetarani?Popup=memberProject&Data=1715058620798x688250005182920000

<b>Problem</b>- Atliq hardware company is not making profit in some regions and country. The performance is going down in various region. AtliQ Hardware, a growing electronics company, faced a major setback in some areas prompting a need for data-driven decisions.

The Solution: Introducing Business Insights 360, a Power BI project that empowers AtliQ with actionable insights across Finance, Sales, Marketing, Supply Chain, and an exclusive Executive View. The data contain all information about sales, region, products, customers, markets, pre invoice deductions, post-invoice deduction, freight cost, manufacturing cost.
<br>
## Step 1
ETL- I loaded the database in sql file into Power bi and did transformation on data.
1) Combined present sales and forcast sales into a table called it fact table(for data modelling)
2) extracted the fiscal year from date and match with company fiscal year which is 4 months ahead using power query
3) joined the tables using power query to extract informative columns like  pre invoice deductions, post-invoice deduction, freight cost, manufacturing cost.

![Powerq](https://github.com/Arunsangeeta/Atliq-Hardware-sales-analysis/assets/110085545/f38c0ba5-98a5-4f33-a3e6-fd5b8214e83b)


## step 2
Data modelling- Using powerBI i combined all tables using one to many relationship. where many to many relationship found,  i converted that to one to many by creating different table called(bridging table) 


![Data modelling](https://github.com/Arunsangeeta/Atliq-Hardware-sales-analysis/assets/110085545/54469b20-ced5-428e-b98d-34aef9f7eda5)

## step3
Created some Measure using Dax formula and custome calculation to ustilise them in power Bi
measures- Profit and lose value for present year, last year, net sales, net profit, gross margin, gross sales etc.(check documentation above)

![MEASURES](https://github.com/Arunsangeeta/Atliq-Hardware-sales-analysis/assets/110085545/8c7f9dc1-1868-4008-b9d8-5907b2d3a7ba)

## step 4 creating dynamic dashboards
I have created 5 dynamic dashboards:
 <b>1) Finance View<b>
 1) It analysed the Profit and loss statement for customers and for the products as well
 2) Added visualization for top and bottom net sales for  customers and products
 3) net sales performance for each customer over 4 years.
 4) Added Key performance indicator like Gross margin, net sales and net profit compared it with benchmark set by company.
 5) also added some slicers to analysed profit, net sales, gm in quaters, year and by targets.

![finance view](https://github.com/Arunsangeeta/Atliq-Hardware-sales-analysis/assets/110085545/2ca2b5e7-d8de-430f-afa8-18d45bc949de)


