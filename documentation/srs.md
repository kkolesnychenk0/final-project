#Distribution control

##Vision
"Distribution control" is web-application which allows users to record information about manufacturers, distributors and outlets.

Application should provide:

-   Storing manufacturers, distributors and outlets in a database;
-   Display list of manufacturers;
-   Updating the list of manufacturers (adding, editing, removing);
-   Display list of distributors;
-   Updating the list of distributors (adding, editing, removing);
-   Display list of outlets;
-   Updating the list of outlets (adding, editing, removing);
-   Display deliveries for distributors and outlets.

##1. Manufacturers
###1.1 Display list of manufacturers
This mode is intended for viewing the list of manufacturers and distributors who work with them.
####Main scenario:
- User selects item “Manufacturer”;
- Application displays list of Manufacturers.
#img

Pic 1.1 View the manufacturers list.

The list displays the following columns:
- Name – manufacturer’s name;
- Code – manufacturer’s code;
- Number of distributors – manufacturer’s number of distributors. Link to the list of shipments to distributors.
- Country - manufacturer’s country.

  