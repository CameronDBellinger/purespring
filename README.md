PureSpring Water Solutions

PureSpring Water Solutions is a PHP/MySQL e-commerce website developed as part of the SDC310L Project: Applying MVC. The project demonstrates database connectivity, dynamic product displays, PHP sessions, shopping cart functionality, checkout/order processing, and contact form processing.

Technologies Used

PHP

MySQL

PDO

HTML5

CSS3

Apache/XAMPP

PHP Sessions

Project Features

Database-driven product catalog

Featured products on the homepage

Product store page

Shopping cart using PHP sessions

Add, update, and remove cart items

Dynamic cart item count

Checkout and customer information collection

Order and order-item database records

Cart clearing after successful checkout

Contact form with database storage

Shared header and footer components

External CSS styling

Database

The project uses a MySQL database named PureSpringProject.

The database contains the following tables:

categories

products

customers

orders

order_items

contact_messages

cart_items

A PDO connection is configured through connect_controller.php.

Running the Project

Install and start XAMPP.

Start Apache and MySQL from the XAMPP Control Panel.

Place the project folder in the XAMPP htdocs directory.

Create/import the PureSpringProject MySQL database.

Verify the database credentials in connect_controller.php.

Open the project in a browser through localhost.

Example:

http://localhost/PureSpringProject/

Project Structure

Key project files include:

index.php – Homepage and featured products

store.php – Product catalog

cart.php – Shopping cart

checkout.php – Checkout and order processing

contact.php – Contact form

about.php – About page

support.php – Support page

header.php – Shared navigation/header

footer.php – Shared footer

connect_controller.php – PDO database connection

conn_status.php – Database connection testing

css/style.css – Website styling

Testing

The application was tested locally using XAMPP/Apache and MySQL.

Testing included:

Verifying the PDO database connection

Loading products dynamically from MySQL

Adding products to the shopping cart

Updating cart quantities

Removing products from the cart

Verifying cart totals

Confirming the dynamic cart count

Completing the checkout process

Verifying customer records are saved

Verifying orders and order items are saved

Confirming the cart is cleared after checkout

Submitting the contact form

Verifying contact messages are saved to the database

Testing navigation and shared site components

All major system components were tested and were functioning as expected at the time of submission.

Project Progress
Week 1 – Database Setup & Connection

Created the PureSpringProject database, configured the PDO connection, created the seven required tables, and inserted sample product/category data.

Week 2 – Dynamic Frontend Integration

Created the main website pages, shared layout components, external CSS, and database-driven product displays.

Week 3 – Shopping Cart & Session Management

Implemented PHP sessions, add-to-cart functionality, cart management, quantity updates, item removal, totals, and the dynamic cart count.

Week 4 – Checkout, Orders & Contact System

Implemented checkout, customer/order/order-item database processing, cart clearing, order completion messaging, and contact message storage.

Author

Cameron Bellinger

SDC310
