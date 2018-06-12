# CuShop

CuShop

Authors:
	
	Adam Farah
	Ashton Woollard Francis



Purpose:
	
	An inventory management program using a doubly linked list
	
	To store product data, with a Facade Design pattern, along with
	new features. 
	Product data is sorted into product categories such
  as taxable, non Taxable, 
	Perishable and non perishable. 
	One step
  further they are sorted into dairy, CoffeeTea, meat, miscGoods,
 and bakery.



Files:
	
	custArray.cc   						- custArray.h
	
	Customer.cc    						- Customer.h
	
	inControl.cc   						- inControl.h
	
	ProdList.cc    						- ProdList.h
	
	Product.cc     						- Product.h
	
	Purchase.cc    						- Purchase.h
	
	PurchArray.cc  						- PurchArray.h
  
	Date.cc        						- Date.h
  
	Perishable.cc  						- Perishable.h
  
	NonPerishable.cc 					- NonPerishable.h
  
	Taxable.cc     						- Taxable.h
  
	NonTaxable.cc  						- NonTaxable.h
	
	TaxationBehaviour.cc 	 				- TaxationBehaviour.h
	
	ExpirationBehaviour.cc 	  				- ExpirationBehaviour.h
  
	Dairy.cc       						- Dairy.h
  
	CoffeeTea.cc   						- CoffeeTea.h
  
	Bakery.cc      						- Bakery.h
  
	Meat.cc        						- Meat.h
  
	MiscGoods.cc   						- MiscGoods.h
	
	Order.cc       						- Order.h
	
	OrderArray.cc  						- OrderArray.h
	
	OrderServer.cc 						- OrderServer.h
	
	store.cc       						- store.h
	
	UI.cc          						- UI.h
 	
	defs.h
	
	main.cc
	
	makefile
	
	readme.txt



Compilation Command
:
	make



Launching and Operating Instructions
:
	Run the program with the following command
	
	./cushop -c or ./cushop -a

	When it launches navigate through the menu as a customer or an admin.

	Purchase a products using the corresponding Costumer and Product ID then 
	enter 42 in the main menu to see your orders.

	Use admin features manipulate inventory in the store
