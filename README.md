 # ParkReservationCapstone

The cohort's second capstone was primarily focused on SQL databases and interacting with them via a C# command-line program. The project's focus was a mock camping ground reservation system accessed and manipulated through the command-line interface. The main components of the project were the dynamic menu system, generated using the data from database tables, branching paths at each layer and logic checking user input, building the data access object layer to extract data from the database and turn it into objects that could be used in the program and then sending updated the data back to the database and using DateTime logic to ensure reservations were made correctly.

There was a very exciting moment in the project when my partner and I were working on the reservation logic and the IDE suggested built-in C# DateTime methods to us. Discovering and implementing those methods simplified our code a bit and saved us some time and energy that would have otherwise gone into working out those details on our own. 

There were also user interface elements added, such as padding, to line up the data rows, give the program a unified look and making the end-user experience as pleasant as possible in a CLI program.


Project Highlights include:

Campground Reservation ran from Command Line with MS SQL Database backend.

MS SQL DB back end for Park and Campground organization.

CLI user interface with minor formatting (Line Padding for Column Organization, etc.)

Data Access Layer / Objects to allow C# to access and modify SQL DB tables.

DateTime Logic for reservation system. It does not allow reservations in past, overlapping reservations, etc.
