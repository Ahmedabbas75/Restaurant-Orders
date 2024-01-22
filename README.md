## 1- Dashboard :
</p>
  <p float="left">
  <img src='resources/restaurant orders.jpg'/>
</p>
__________________________________________________________________________________________________________________________

## 2- Tables Description :

| Table	| Field	| Description |
|-----|----------------|--------------- |
| menu_items	| menu_item_id	| Unique ID of a menu item |
| menu_items	| item_name	| Name of a menu item |
| menu_items	| category	| Category or type of cuisine of the menu item |
| menu_items	| price	| Price of the menu item (US Dollars $) |
| order_details | order_details_id |	Unique ID of an item in an order |
| order_details |	order_id |	ID of an order |
| order_details| order_date |	Date an order was put in (MM/DD/YY) |
| order_details | order_time |	Time an order was put in (HH:MM:SS AM/PM) |
| order_details |	item_id | 	Matches the menu_item_id in the menu_items table |

__________________________________________________________________________________________________________________________

## 4- In Mind Questions :
- ### General Questions related to the existence of :
  - missing values?
  - wrong datatypes for columns?
  - complete duplicates in the data?
  - outliers in numerical columns?
 
- ### Business Questions :
  - What were the least and most ordered items? What categories were they in ?
  - What do the highest spend orders look like? Which items did they buy and how much did they spend ?
  - Were there certain times that had more or less orders ?
  - Which cuisines should we focus on developing more menu items for based on the data ?
﻿﻿
﻿
