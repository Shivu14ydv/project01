<h1 align="center">Shopping-Ecommerce-App-Project</h1>
<h3 align="center">Online shopping App built on Android Studio and Firebase Realtime Database.</h3>
This is an online shopping app developed by me.I started developing this app in February 2021 for my self-learning, sheer interest in android development and my project



<h2>LANGUAGES USED:</h2>



1.JAVA


2.XML :FOR LAYOUT

                                                                         
                                                                         
<h2>TOOLS AND TECHNOLOGIES USED:</h2>



1.ANDROID STUDIO(FOR DEVELOPMENT PURPOSE)



2.FIREBASE REALTIME DATABASE

                                                                   
                                                                   
<h2>DESCRIPTION OF EACH ACTIVITY/JAVA FILE:</h2>



1.MAIN ACTIVITY:
<br>
Welcome screen of the app which shows the app logo and a background for 2 seconds and then proceeds to the next activity.
<br>


2.REGLOGCHOICE:
<br>
Activity providing choice between user register,user login,admin login,staff login and about section.
<br>

3.REGISTER PAGE:
<br>
Registers a new customer/user onto the online database after asking their credentials
<br>

4.MEMBERREG:
<br>
Java file containing constructor to initialize database objects for users and functions to get(return) characteristics(variables) for each object.
<br>

5.LOGIN PAGE:
<br>
Login screen which logs in registered users.
<br>

6.HOME PAGE ACTIVITY:
<br>
Home page for customers where they can choose their category of items to shop
<br>

7.MENS CLOTHING,8.WOMENS CLOTHING,9.TSHIRTS,10,BOTTOM WEAR,11.SHOES,12.FORMALS,13.BOOKS,14.ELECTRONICS,15.OTHER ITEMS,16.CLOTHING:
<br>
Activities for displaying items or subdivisions within the category of respective Activity name.
<br>

17.RECYCLER ADAPTER:
<br>
Adapter class for displaying items in a recycler view
<br>
18.DISPLAY ITEM:
<br>
Display selected item from recycler adapter individually
<br>

19.PLACE ORDER:
<br>
Push ordered item details and customer information into Order database and upload it on Firebase.
<br>

20.ORDERS
<br>
Java file containing constructor to initialize database objects for placed orders and functions to get(return) characteristics(variables) for each object.
<br>

21.ADMIN LOGIN:
<br>
Login Page for admin of the organization(app company)
<br>

<b>ADMIN USERNAME-smartkart
<br>
ADMIN PASSWORD-appadmin123</b>
<br>
22.ADMIN HOME PAGE:
<br>
Home page for admin displaying options for the tasks which he/she wants to perform
<br>

23.ADD STOCK
<br>
Add stock of each item availaible on the app by updating data on StockReg database
<br>

24.STOCKSREG
<br>
Java file containing constructor to initialize database objects for items and functions to get(return) characteristics(variables) for each object.
<br>
25.ADD STAFF
<br>
Add staff(delivery boy) by pushing the details of the staff through an object of StaffReg class onto the Firebase Reatime Database
<br>

26.STAFFREG
<br>
Java file containing constructor to initialize database objects for staffs and functions to get(return) characteristics(variables) for each object.
<br>

27.STAFF LOGIN
<br>
Login Page for staffs/delivery boys and then decide whether to show current orders menu or redirect to orders assigned to the staff depending of the current state of the staff.
<br>

28.ACCEPT ORDERS
<br>
The staff can accept and order to deliver from this activity.The order selected to deliver is added as an object to a new database called DeliverOrder and removed from Orders.This differentiates order which are only ordered to those orders which are ordered and currently under delivery.After this acceptance ,staff is redirected to Current Order Status to finalize/confirm delivery when he delivers the order to customer in personal
<br>

29.DELIVER ORDER
<br>
Java file containing constructor to initialize database objects for orders currently under delivery and functions to get(return) characteristics(variables) for each object.
<br>
30.CURRENT ORDER STATUS
<br>
To confirm delivery ,the customer must enter his password when the order is delivered to him by the staff.This deletes the specified order object from DeliverOrder and proves that the order has been successfully delivered to the customer.
<br>

31.ABOUT
<br>
Activity displaying the details of the developer and link to his social media handles.
<br>


<h3><i><center>THANK YOU FOR READING THE DESCRIPTION OF THIS PROJECT,POINTERS TO FURTHER IMPROVEMENTS IN THIS PROJECT ARE ALWAYS WELCOME</center></i></h3>


