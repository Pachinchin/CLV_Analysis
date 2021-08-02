# CLV_Analysis
Analysis of customer lifetime value using three different method. 

1. Average of all sum \
2. Cohort Analysis \
3. BG/NBD Model (with Gamma-Gamma extension)

Dataset Info:
This is a customer orders database, part of the superstore data in Tableau. it contains orders occurring between 2014-01-03 and 2017-12-30.

Attribute Information:
Row ID:
Order ID:       Unique identify of an order. 
Order Date:     Order Date. Numeric, the day when each transaction was generated.
Ship Date:      Order Date. Numeric, the day when each shipment was made.
Ship Mode:      Method of shipment selected by the user
Customer ID:    Customer number. Nominal, an alphanumeric ID uniquely assigned to each customer.
Customer Name:  Nominal, the First and Last name of each customer.
Segment:        Customer Segment classification
Country:        Country name. Nominal, the name of the country where each customer resides.
City:           City name. Nominal, the name of the city where each customer resides.
Postal Code:    Postal code according to the address of the customer.
Region:         Geographic Region, of the country or state.
Product ID:     Unique id for the product sold 
Category:       Product category classification
Sub-Category:   A subcategory of the product category
Product Name:   Nominal, a name of the product.
Sales:          Sales Amount. the value of the product sold
