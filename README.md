This was a workplace improvement project. All data used are generic and non-classified. This is only a test version with trial functionalities.

The access file consist of 2 main parts:
  1. Forms (enter "Design View" to see the code behind the form components)
     - Main page
     - Log in page
     - Book out session page
  2. Reports
     - Show Current Status of Items
     - Show All Transaction Records

See Module <mod1> for generic functions used.

Brief functionality:
1. Users access the main interface and click on what they wanted to do, (a) Book out / return items or (b) Check status / records.
2. Upon clicking into booking / out items button, "Log In" page will show.
3. Users will key in their account details and a validity check will be done against the database.
4. Once verified, the "Book out session" page will show for users to key in their requested items.
5. Upon keying in the item code (on event "lose focus") a check will be done against the permission to verify if user is allowed to book out the item.
6. Once verified, item and user details will be appended to the "Temp" table and be displayed to user.
7. Once confirmed, all details will be appended into the "Transaction" table.
8. The reports queries and displays current item status and transactions for export.
