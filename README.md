# Titanic_Dataset_SQL_Server_Script
It's a script to fill in a defined table in SQL server database with Titanic data. This script is generated from a .csv file containing the original data in csv format. It's assumed that the defined table's name is Titanic and that it contains the following columns : 
1 - Passenger_id (primary key and int). 2 - Survived (tinyint). 3 - Pclass (tinyint). 4 - LastName (varchar(100)). 
5 - FirstName (varchar(100)). 6 - Gender (char(6)). 7 - Age (float). 8 - Sibsp (int). 9 - Parch (int). 10 - Ticket (varchar(100)). 
11 - Fare (float). 12 - Cabin (varchar(100)). 13 - Embarked (varchar(3)).

All columns allow null values (as there are missing data in the original file) except for the primary key Passenger_id.

Columns description :
--------------------
1 - passenger_id : unique id for each passenger.
2 - Survived : whether survived the disaster. either 0 (didn't survive) or 1 (survived).
3 - Pclass : the ticket class. either 1, 2, or 3.
4 - LastName : passenger last name.
5 - FirstName : passenger first name.
6 - Gender : either male or female.
7 - Age : passenger age.
8 - Sibsp : number of siblings or spouses on the ship.
9 - Parch : number of parents or children on the ship.
10 - Ticket : ticket id / name.
11 - Fare : fare paid.
12 - Cabin : number of cabin.
13 - Embarked : port of embarkation either S (Southampton), C (Cherbourg), or Q(Queenstown).
