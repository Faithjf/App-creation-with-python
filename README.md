# App-creation-with-python
This is a grocery app that helps supermarket calculate total price at checkout point. The app also updates inventory when new products are bought, likewise (reduce) when products are sold.


### The following are some of the highlights from the process of building the app.

# Use_cases
**1. An app that manages inventories and sales**

>**_Inventory management:_**
>
>>* Restocking inventory when the grocery store buys new stock
>>
>>* Sales reduction from inventory when an item is sold to a customer. 
>
>All inventory were managed by restocking and reducing the stick avaliable

>**_2. Generate sales receipts for customers:_**
>
>>* Compute sales by item and  selling price
>>
>>* Compute total sales for each customer 
>>
>>* Print out the summary of the purchase sales for each item per customer. 
>
> By computing the sales receipts, I was ables to show the total sales by items purchased

**3. This app also has an inbuilt system that raises alarm once any inventory falls below 5 items.**

In this section, the symstem automatically raise an alert whenever the items in each of the product inventory gets to 5 or below

# The Model:

In this model, I used a jupyter notebook to arrange all items in the store into a dictionary container. The inventory includes Cosmetics inventory, pastry inventory, beverage inventory, etc. I was able to build a code that updated the inventory dictionary once an item was removed or added. 

I created another dictionary to hold the prices of each item available in each inventory,  and if a product that doesn't exist was selected, the app returns a default statement " item isn't available for sale"

When I was done inputting all necessary parts of this project, I imported pandas to enable me to generate the receipts for each customer
