# Inventory-Management-Dashboard-in-Power-BI

# For the fully interactive Power BI report, please view my portfolio on https://www.novypro.com/project/inventory-management-dashboard-1

### Introduction

The development of this dashboard involved the extraction of data from an om-premise data warehouse in SQL Server Management Studio using views. The dataset consists of approximately 5 million rows. This inventory management solution allows for users to search items by SKU number and examine how various inventory metrics fluctuate in certain time periods.


### Data Preparation

<img width="995" alt="image" src="https://github.com/rcfrazier127/Inventory-Management-Dashboard-in-Power-BI/assets/63532077/5a352189-1a69-433e-9ef7-d0e31bbb7bc1">

Since this data was uploaded from a source containing Microsoft's Contoso sample dataset it is very clean. The only preprocessing methods used were the removal of irrelevant columns and proper formatting of the data to establish consistency in this particular use case.


### Data Model

<img width="765" alt="image" src="https://github.com/rcfrazier127/Inventory-Management-Dashboard-in-Power-BI/assets/63532077/9ef0d836-a965-461e-a80f-462ddb3e1484">

The data model is very simple and conists of a central fact table followed by multiple dimension tables and a measures table.


### Dashboard

<img width="1482" alt="image" src="https://github.com/rcfrazier127/Inventory-Management-Dashboard-in-Power-BI/assets/63532077/e002196f-bbd7-4c16-bf09-c21e4df56190">

The upper row of KPIs were created using the newly updated verison of Power BI's "KPI card" visual. The main functionality of this dashboard is the ability to lookup individual SKU's to isolate items and further examine inventory metrics, such as stock turnover, stock value, items in stock, items on order, return rates, and other relevant financial figures. The inclusion of historical data is to allow users to examine previous periods to view how trends, rates, and demand has behaved over time. Visuals can be toggled via bookmarks to examine weekly trends, how stock is broken by stock type (high, mid, and low moving stock), and measuring sales and total stock value against COGS over time. 


<img width="1481" alt="image" src="https://github.com/rcfrazier127/Inventory-Management-Dashboard-in-Power-BI/assets/63532077/e0ea4477-0033-4a45-b52f-743a53e48a4b">

The screenshot above is the view seen when the "Total Value" bookmark is selected. "Units Sold" is not displayed because it is identical to "Total Sales."
