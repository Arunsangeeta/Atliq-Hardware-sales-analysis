<p4>Atliq-Hardware-data- analysis</p4><br>
Currently ongoing project

<b>Problem</b>- Atliq hardware company is not making profit in some regions and country. The performance is going down in various region. The data contain all information about sales, region, products, customers, markets, pre invoice deductions, post-invoice deduction, freight cost, manufacturing cost.
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

## step 4 Dashboard - currently working on it
Finance view

![finance view](https://github.com/Arunsangeeta/Atliq-Hardware-sales-analysis/assets/110085545/2ca2b5e7-d8de-430f-afa8-18d45bc949de)


