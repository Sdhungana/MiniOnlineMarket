# MiniOnlineMarket

1.Admin	

   a.	If the seller registers to the web site, he/she need to get approval from Admin in order to post products.	
   b.	The admin should approve the reviews that are made from the Buyers.	
2. Seller	
  a.	Register as Seller		
  b.	Product (CRUD). If a product has already been purchased, it cannot be deleted.	
  c.	Seller cannot buy products from the website	
  d.	Maintain orders 
  a)	Cancel Order, the status of order on buyer’s part should also changed
  b)	Change Order status (Shipped-On the way-Delivered)	
  
3. Buyer	
  a.	Register as Buyer	
  b.	Follow and Unfollow Seller	
  c.	Cannot sell items on this website	
  d.	Can place an order
  a)	Maintain Shopping Cart (CRUD)
  b)	Maintain Shipping and Billing Address
  c)	Maintain Payment
  d)	Place order
  e)	Every successful purchase (not returned), gain points from the website. You can use points to buy products (something like coupons)	
  
4. Maintain Orders
  a)	Check Order History
  b)	Can cancel order before shipping, after shipping cannot
  c)	Download/Print receipt as PDF or Excel
  d)	Write Product Review. Review must be approved by Admin before live.

  5. General		
  Login/Logout	
  Security with JWT (Users should not be able to access other pages links)	
  Process verifications etc. (user get email of purchase, gets a message)	
  Validation is required for all form submission. Otherwise, you’ll not get full credit on different feature part.	
