The first package "Basis" contains two classes named "Calculator" and "Calc" which are responsible for the price with and without a discount, in case of increasing or decreasing discounts on products you have to change the classes only in one package (by listening to the principles), as well as two interfaces "IIProduct" and "IProduct". 


The second package "Shop" has 4 packages, two of them are "Shop" and "SShop" which are responsible for the initial amount and what products are available. at any time you can change the price of any product and also add to the assortment itself without changing anything in the other packages. The other two classes are "Namesofflourprod" and "Namesofgardenproduct", they contain product names and are responsible for the fact that when the user enters an input, these classes look for a match and display the desired product and amount.
The third package "Company" contains the main class which connects the packages and runs the code

The principles are respected, the objects that change for the same reason at the same time are contained in one package,
without affecting other packages
