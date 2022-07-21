# Hotel-Room-ManageMent

Hotel Room Management tool which can be used to manage activities like storing customer details,booking rooms of four different types, oredering food for particular rooms, unbookiing rooms and showing the bill.
we can be used to see different room featues and room availibility. it is a menu driven program and it runs until the user exits.
File handling has been used to store the current status of the hotel(Customer Details, booked rooms,food ordered) in a file once the program exits so that when we restart the program , the old detaisl are not lost.
The program reads the file when it restrats to know the previous status of the hotel. writing of file has been done in a separate thread as it can be done parallely.
user defined exception is thrown if user tries to book and already allotted room.
Exception handling is properly done to deal with andy kind of unexpected exception.


input and output

Enter your choice:
1.Display room details
2.Display room availability
3.Book
4.Oreder food
5.Checkout
6.Exit

1. Display room:

Choose room type:
1.Luxury Duble Room
2.Deluxe Duble Room
3.Luxury Single Room
4.Deluxe Single Room

2. Display room availability

Choose room type:
1.Luxury Duble Room
2.Deluxe Duble Room
3.Luxury Single Room
4.Deluxe Single Room

3. Book

Choose room type:
1.Luxury Duble Room
2.Deluxe Duble Room
3.Luxury Single Room
4.Deluxe Single Room

4.Oreder food
Room Number- example=9
==========
   Menu:
==========

1.Sandwich      Rs.50
2.Pasta         Rs.60
3.Noodles       Rs.70
4.Coke          Rs.30
Enter your Choice(1/2/3): example(1)

Quantity- example:2

Do you want to order anythin else(Y/N):

5.Checkout:
Food Charges:-
===============
Item   Quantity    Price
-------------------------
Sandwich  2         100.0
Pasta     2         120.0

Total Amount- 4220.0
Deallocated succesfully




How works:


