# business360
**This was a project made for AtliQ's Hardware company**

**Getting Understanding of Data - ETL**

[x] Loaded Data in Power Bi

AtliQ's hardware consisted in three different databases:

 ***Dimensional tables***

  
**Dim_customer** - A dimensional table containing **"customger"**, **"market"**, **"Platform"**, **"Channel"** and **"customer_code"**.
  
  [x] **"customer"** - The names of customers which AtliQ's Serve
  
  [x] **"market"** - The names of countries that AtliQ's Serve
  
  [x] **"Platform"** - AtliQ's Retailer's can be Brick and Mortar or E-commerce, which are the platforms available
  
  [x] **"Channel"** - AtliQ's channels are ***"Direct Channel"*** in which AtliQ's has it's own Stores (AtliQ's Exlusive and AtliQ E Store), ***"Retailer"*** in which AtliQ sends its products to be sold to the final consumer, and ***"Distributor"** channel, in which AtliQ has distributores in countries that do not allow Retail or Direct Sell. 
  
  [x] **"Customer_code"** A unique code for every customer **"customer"**

  
**Dim_market** - A dimensional table containing **"market"**, **"subzone"** and **"region"**.

  [x] **"Market"** - List of countries that AtliQ Serve - Unique
  
  [x] **"Subzone"** - The zone code atributed to each country
  
  [x] **"Region"** - The region code atributted to each country
  
  
**Dim_product** - A dimensional table containing **"product_code"**, **"division"**, **"Segment"**, **"category"**, **"product"** and **"variant"**

[x] **"Product_code"** - A unique code for every **"product"**

[x] **"Division"** - The codes for the divisions of AtliQ's Hardware products - e.g Computers, Accessories...

[x] **"Segment"** - The names for each sub-category inside "**division"**

[x] **"Category** - The names for each category of products.

[x] **"Product"** - The names for each product.

[x] **"Variant"** - The variant for each product - States if it's some sort of premium product


 ***COGS tables***


**freight_cost** - A table containing **"market"**, **"fiscal_year"**, **"freight_pct"**, and "**other_cost_pct"**

[x] - **"market"** - The names of countries that AtliQ's Serve.

[x] - "**fiscal_year"** - The fiscal year of the **"freight_pct"** and **"other_cost_pct"** attributed to each market.

[x] - **"freigh_pct"** - The % of cost that goes for shipping for each country that AtliQ serves.

[x] - **"other_cost_pct"** - The % of other costs that goes for selling for each country that AtliQ serves.

**manufactoring_cost** - A table containing **"product_code"**, **"cost_year"** and **"manufactoring_cost"**

[x] - **"product_code"** - The product codes found in the ***"dim_product -> product_code"*** table

[x] - **"cost_year"** - The fiscal year of the **"gross_price"** attributed to each market.

[x] - **"manufactoring_cost"** - The cost of manufacturing for each product by the year.










**gross_price** - A table containing **"product_code"**, **"fiscal_year"** and **"gross_price"**

[x] - **"product_code"** - The product codes found in the ***"dim_product -> product_code"*** table

[x] - **"fiscal_year"** - The fiscal year of the **"gross_price"** attributed to each market.

[x] - **"gross_price"** - The price charged by AtliQ's for each product.


