CS 3500 Project - Restaurant Website
Authors: Gregory Smith (OryGregS), Jonah Kubath (jkubath), Matthew Peter
(mpeter97)

This website mostly utilizes PHP and SQL. Built using bootstrap, the website will scale to any device. Database design and implementation credit goes to Matthew Peter (mpeter97).

Instructions to view the website:

  1) Open XAMPP or an equivalent and run Apache and MySQL. If you do not
     have XAMPP or an equivalent, this website will not run without it.
  2) Place all files under htdocs. Example file path: "C:\xampp\htdocs".
  3) Create a database in "http://localhost/phpmyadmin/" named "restaurant".
  4) In the restaurant database, navigate to the "Import" tab.
  5) Browse your computer for the file "restaurant.sql" that is
     included.
  6) Click "Go" to import the database information.
  7) In your browser, go to the address
     "localhost/CS3500Project/PHP/Main.php"
  8) Enjoy!

Information about the website:

  There are 4 different levels of accounts.
      1. Customer
      2. Employee
      3. Manager
      4. Owner

  Usernames:
      Customer -> customer1
      Employee -> employee1
      Manager  -> manager123
      Owner    -> owner1

  Passwords:
      First 5 letters of Username + Numbers at end of Username + "Password"

  The header will navigate you to wherever you want to go. The footer social links will link you to the base website. Since this is a fictional restaurant, we do not have social media accounts for it.

  Menu items change by location, so not every store will offer the same things.     

  Leaving a comment or concern will upload it to the database. A manager or owner can then choose which comments they want to add to the review carousel on the main page.

  Customers can place orders that will be added to the database. Any higher level account can see these orders. Customers can also create "custom burgers" that they can save under their account.

  Employee's can see customer orders -- but it requires a manager to login.

  Managers can see customer orders, edit the menu at the location they work at, and retrieve information about their store.

  Owners can do everything the lower level's can, and also edit the products that are offered at every store.


Please play around with it and enjoy!
