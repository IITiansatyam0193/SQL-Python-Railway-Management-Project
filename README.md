# RAILWAY MANAGEMENT SYSTEM

---------
:FOLDERS:
_________

/Assets : Contains the data that is to be inserted in the MySQL tables in csv format
         
Train_details.csv -> Contains all the data about the trains in the format (Train No, Station Code, Station Name, Arrival time, Departure Time, Distance, Source Station, Source Station Name, Destination Station, Destination Station Name)

/core : Contains all the files that are required by the project to work

__init__.py -> Makes the folder to be recognized as a module
Checks.py -> This file contains the functions that verify the requirements of the Project
InsertData.py -> This file contains the functions to insert the data in the MySQL tables
User_Functions.py -> This file contains the function that allow a user to perform certain task
Other.py -> This file contains some commonly used functions

-------------------
:ROOT FOLDER FILES:
___________________

Main.py -> This is the main file that connects all the other modules and is used to run the project

requirements.txt -> It contains the required packages for this project to work that can be installed via the command `pip3 install -r requirements.txt`
