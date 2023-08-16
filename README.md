# business360
**This was a project made for AtliQ's Hardware company**

**ETL Phase**

[x] Loaded Data in Poower Bi
AtliQ's hardware consisted in three different databases:
  **Dimensional tables**
    [x] Dim_customer - A dimensional table containing **customer**, **market**, **Platform**, **Channel** and **customer_code**
      [x] **customer** - The names of customers which AtliQ's Serve
      [x] **market** - The names of countries that AtliQ's Serve
      [x] **Platform** - AtliQ's Retailer's can be Brick and Mortar or E-commerce, which are the platforms available
      [x] **Channel** - AtliQ's channels are ***Direct Channel*** in which AtliQ's has it's own Stores (AtliQ's Exlusive and AtliQ E Store), ***Retailer*** in which AtliQ sends its products to be sold to the final consumer, and ***Distributor** channel, in which AtliQ has distributores in countries that do not allow Retail or Direct Sell.
      [x] **Customer_code** The code names for **customer**.
    [x] Dim_market - A dimensional table containing **market**, **subzone** and **region**
    [x] Dim_product - A dimensional table containing **product_code**, **division**, **Segment**, **category**, **product** and **variant**
