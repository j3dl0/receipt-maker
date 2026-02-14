Receipt Maker Project

A receipt generator for a 10 item or less checkout lane. Stores item name and price into arrays, which then gets displayed in a list. There are two lists: Stats and Breakdown. Stats list the name and price of the cheapest and most expensive items along with the mean price of the total items purchased. The breakdown just lists the name and price of the items purchased. Once finished, the final receipt calculates the subtotal of the items, the tax (New York tax rate), and then calculates the total due.

How to Compile & Run:
javac ReceiptMaker.java
java ReceiptMaker

Usage Instructions:
Enter item name and price separated by a space, or enter "checkout" to end transaction early. Max item amount: 10.

Things to Note:
Does not handle InputMismatchException
Fixed tax rate set to NYC rate.

Corrections made to ReceiptMaker:

addNextPurchaseItemFromUser - correctly assigns values and increments once.
getMinPrice - uses Double.MAX_VALUE.
getMaxPrice - Double.MIN_VALUE.
getIndexOfMaxPrice - correctly assigns i.
displayReceiptStats - Printf formatting corrected.
