# Cafe12
The Cafe12 application will be used by a variety of staff with different mobile devices with different Operating Systems. As a result, the app will be written using Flutter, a cross platform mobile development library.

![Business Process](Business%20Process.png)

The application will have 3 different modes which are suitable for a member of staff depending on their role. The modes are as follows:
1. Waiter
2. Bartender/Chef
3. Boss

## Waiter
Waiter mode will allow staff to take customer order requests and send the orders to a centralised database.
The up-to-date menu will be supplied to the Waiter to provide easy and simple selection.
In the event of a user making a special request with their order, the Waiter will be able to attach text notes to the order.
The Waiter will also be able to make any amendments to the order in case there is a complication or error.
If the Bartender/Chef needs to speak to the Waiter, the Waiter will be notified.

## Bartender/Chef
Bartender/Chef mode will allow staff to see on their side of the application what has been ordered by customers in order to prepare for their orders.
The reason why the Bartender and Chef roles aren't separated is because it is possible that the member of staff using the app could be both the bartender and the chef.
In Bartender/Chef mode, the user will be able to filter what orders they receive. For example, if they wanted Bartender mode only, they will only see drinks (and simple snacks) orders. If they wanted Chef mode only, they will only see Hot Food orders.
If there is an issue with an order from the perspective of the Bartender/Chef, they will be able to attach a note to the order for the Waiter, or they can press a button to summon a Waiter.
A member of staff will also be able to mark a product as out of stock which will prevent a Waiter from selecting that order.

## Boss
Boss mode is specifically for the head of the Cafe (or for a trusted member of management).
This mode will provide advanced features such as changing what's on the Menu and the domain (or IPv4) of the REST API Server.
To activate this mode, the user will be required to enter a super password and will be located within the settings.

# Summary
In summary, v1.0.0 will have the following features:

### Waiter
- Select a variety of available Menu items provided by the API server
- Send customer orders to the server for the Bartender/Chef
- Provide notes to a customers order to allow customization/special requests as part of an order
- Make amendments to an order already processed
- See orders ready to send to the customer
- Receive a request when the Bartender/Chef needs to speak to them

### Bartender/Chef
- See orders sent from the Waiter
- Mark a product as out of stock
- Filter processed orders
- Attach notes to the orders
- Summon staff running Waiter mode

### Boss
- Password Protection
- Amend Menu
- Change API Server Destination