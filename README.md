# Build a Fake Shopping App

Objectives: UML, Classes, Abstraction, Polymorphism, Inheritance, Interface, static, Arrays, ArrayList, Loops etc.
- All the properties/instance variables can be seen in the UML. Read the UML!

![FinalShopAppUml](https://user-images.githubusercontent.com/10773482/113274582-dbd27d80-92ab-11eb-85e3-d868c877cafc.png)

## Part 1

### Company Discount Policy!!!
- All employees get a 10% discount off a clothing Item
- However Managers get 25% off  a clothing Item;

### Instructions:
- Instantiate 3 Clothing objects
- Create a managerCart array which contains all three clothing objects.
- Create a manager object.
- Create an employeeCart array which contains all three clothing objects
- Create an employee object.
- Use the Shop App to Check and print the total of your manager's cart
- Check if one of the clothing items fits one of your customers and print out the outcome - make sure it works!!!
- Print the hourlyEmployee's price after discounts on any two of the clothing items. Just print them out
- Print the manager's price after discounts on the same clothing items you discounted for the hourly employee to see the difference
- Create an ArrayList of clothing items, add some clothing items to the list and print each item with a for each loop
- Invoke the printEmployeeName method on each employee object to print out their names, one at a time.

## Part 2

- CREATE A METHOD IN THE SHOP APP named printDiscAmtOff 
- It's job is to print out the discount amount of a clothing Item for all types of employees For example: 
- Let's say a pair of Jeans cost $20
- The $ discount amount for a manager will be ```5.00``` while the discount printed for an employee will be ```2.00```

Finally ...phew - invoke the sortAndPrintClothingItemsByPrice on the ShopApp and pass in the ArrayList you created inside main(). - hint: You need to implement the Interface Comparator<T>

# Sample Data
```
        Clothing jeans = new Clothing("Blue Jeans", 20, 'M');
        Clothing tShirt = new Clothing("White T Shirt", 5.0,'S');
        Clothing buttonUp = new Clothing("Button Up Shirt", 30.0, 'L');

 ```
# Expected Output
Just print out the outcomes of your method and separate with a print out message like  `Checking if a clothing items fits an employee` result is false or true

- Total of Manager's cart
-  ``` 55.0```
- Checking if a clothing items fits an employee  
- ```false```
- Hourly employee price for Jeans after discount  
- ```18.0```
- Hourly employee price for tShirt after discount 
- ```4.5```
- Manager price for Jeans after discount 
- ```15.0```
- Manager price for tShirt after discount
- ```3.75```
- Prior to sorting - clothing objects by price  
- ```Clothing{description='Blue Jeans', price=20.0, size=M}```
- ```Clothing{description='Button Up Shirt', price=30.0, size=L}```
- ```Clothing{description='White T Shirt', price=5.0, size=S}```
- After sorting - clothing items by price by Implementing the Comparator Interface!!!
- ```5.0```
- ```20.0```
- ```30.0```
- Printing each type of Employee's name
- ```Jim Jones```
- ```Mike Jones```
- Discount off specific clothing (jeans) for each employee..meaning how much discount they get off
- ```2.0```
- ```5.0```
