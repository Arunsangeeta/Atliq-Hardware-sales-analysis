
<p4>Atliq-Hardware-Business analysis</p4><br>

To check live project please refer my novyproportfolio below:<br>
https://www.novypro.com/profile_about/sangeetarani?Popup=memberProject&Data=1715058620798x688250005182920000

<b>Project Explanation </b>- Atliq hardware company is not making profit in some regions and country. The performance is going down in various region. AtliQ Hardware, a growing electronics company, faced a major setback in some areas prompting a need for data-driven decisions. So, Introducing Business Insights 360, a Power BI project that empowers AtliQ with actionable insights across Finance, Sales, Marketing, Supply Chain, and an exclusive Executive View. The data contain all information about sales, region, products, customers, markets, pre invoice deductions, post-invoice deduction, freight cost, manufacturing cost.
<br>
# Intial steps Before analysis: 
## Step 1- ETL( Extract, Transform and Load)
ETL- loaded the sql file data into Power bi and did transformation on data as Below.
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
I have created 5 dynamic dashboards:<br>
 <b>1) Finance View<b><br>
 1) It analysed the Profit and loss statement for customers and for the products as well
 2) Added visualization for top and bottom net sales for  customers and products
 3) net sales performance for each customer over 4 years.
 4) Added Key performance indicator like Gross margin, net sales and net profit compared it with benchmark set by company.
 5) also added some slicers to analysed profit, net sales, gm in quaters, year and by targets.

![p2](https://github.com/Arunsangeeta/Atliq-Hardware-sales-analysis/assets/110085545/4d920e33-327e-435f-a1c4-568b4a2c5e9b)

<br>
 <b>1) Finance View<b><br>
 1) It analysed the Profit and loss statement for customers and for the products as well
 2) Added visualization for top and bottom net sales for  customers and products
 3) net sales performance for each customer over 4 years.
 4) Added Key performance indicator like Gross margin, net sales and net profit compared it with benchmark set by company.
 5) also added some slicers to analysed profit, net sales, gm in quaters, year and by targets.

![p3](https://github.com/Arunsangeeta/Atliq-Hardware-sales-analysis/assets/110085545/d77532ce-f1fd-4414-a708-872dd46fae62)

<br>
 <b>1) Finance View<b><br>
 1) It analysed the Profit and loss statement for customers and for the products as well
 2) Added visualization for top and bottom net sales for  customers and products
 3) net sales performance for each customer over 4 years.
 4) Added Key performance indicator like Gross margin, net sales and net profit compared it with benchmark set by company.
 5) also added some slicers to analysed profit, net sales, gm in quaters, year and by targets.

![p4](https://github.com/Arunsangeeta/Atliq-Hardware-sales-analysis/assets/110085545/9e946126-141f-4e34-8e54-0f7a85b37189)

<br>
 <b>1) Finance View<b><br>
 1) It analysed the Profit and loss statement for customers and for the products as well
 2) Added visualization for top and bottom net sales for  customers and products
 3) net sales performance for each customer over 4 years.
 4) Added Key performance indicator like Gross margin, net sales and net profit compared it with benchmark set by company.
 5) also added some slicers to analysed profit, net sales, gm in quaters, year and by targets.
  
![p5](https://github.com/Arunsangeeta/Atliq-Hardware-sales-analysis/assets/110085545/efa6b1ad-f1e3-4231-9003-199ecd952060)

<br>
 <b>1) Finance View<b><br>
 1) It analysed the Profit and loss statement for customers and for the products as well
 2) Added visualization for top and bottom net sales for  customers and products
 3) net sales performance for each customer over 4 years.
 4) Added Key performance indicator like Gross margin, net sales and net profit compared it with benchmark set by company.
 5) also added some slicers to analysed profit, net sales, gm in quaters, year and by targets.

![p6](https://github.com/Arunsangeeta/Atliq-Hardware-sales-analysis/assets/110085545/e490be3c-36aa-4868-99d3-f8731a112186)
