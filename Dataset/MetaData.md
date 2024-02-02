
# Stock

|Column | Description |
|------|-------------|
| SKU-ID | Item's identity code, also known as stock keeping unit (SKU) or simply ID |
| Description | The attributed common name of an item |
| 2020_units_sold | Total amount of units sold in 2020 |
| 2021_start_stock | Amount of units in stock at the beginning of 2021 |

# Order

|Column | Description |
|------|-------------|
| InvoiceNo | Unique code referring to a transaction for one or multiple items |
| SKU | Item's identity code, also SKU-ID or simply ID |
| InvoiceDate | Date of purchase for a particular item in an order |
| Quantity | Amount of units sold for a particular item in an order |
| Country | Code indicating the customer ID and the country of origin for the customer |


# Customer

|Column | Description |
|------|-------------|
| CustomerID | Code assigned to each customer on purchase |
| InvoiceDate | Date of purchase for a particular item in an order |


# Country
|Column | Description |
|------|-------------|
| InvoiceNo | Unique code referring to a transaction for one or multiple items|
| Country | Country of origin for the customer ordering the items|


# Price
|Column | Description |
|------|-------------|
| ID   | Item's identity code, also known as SKU-ID or SKU |
| Retail_Price | Item's value at sale poin


# Costs
|Column | Description |
|------|-------------|
| SKU | Item's identity code, also known as SKU-ID or ID |
| raw_material | Item's cost attributed to raw materials used in manufacturing process |
| factory_labor | Item's cost attributed to manufacturing human resource |
| factory_equipment_rent | Item's cost allocated to the rent of equipment for manufacturing of goods |
| distribution | Item's cost associated with the delivery of goods to the buyer |
| advertisement | Item's cost of marketing for a particular item |


# Categories
|Column | Description |
|------|-------------|
| ID | Item's identity code, also known as SKU-ID or SKU |
| category | Item's class assigned to the item |











