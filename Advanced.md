Your eCommerce business needs to keep track of products and their prices. The products each belong to a department. The business needs to keep track of revenue as product prices change over time. The business also needs to keep track of receipts of transactions and the number of units each product has in stock.


* transaction
------------
		date: DateTime,
		products: [
  		{productID, quantity: INT, price: Num},
    	{productID, quantity: INT, price: Num}
    ]
 

* department
------------
		products: [
			{productID, stock: INT, price: Num},
			{productID, stock: INT, price: Num}
		]