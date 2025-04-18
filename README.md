# Assignment 3
## Script to get staff requisition info
it is a basic python script which prompts the user for a few fieds to get some basic staff booking information, generates a requisition ID, and prints the results in a nicely formatted way.
This is also a good beginner project that will help someone that's learning how to user input, variables, and print statements in python.
## What this scripts does
### Takes user input for:
date of the request
staff ID 
Staff name
## Deliveries a basic requisition ID
### Outputs all gathered information to the display
for this you could use a simple internet system in which employees request services or resources and then get confirmation that their entry was recieved.
## code explanation, line by line
### python
Date = input (Enter date)
this line promopts the user for the date. Anything the the user types, the variables date saves.
### staff_id = input (staff id)
this promopts the user for their staff id. the variables staff id stores the input.
### staff_name = input (staff name)
this prompts the user to enter their name. set var staff name to entered name.
### counter = 1
that initializes a variables counter to be 1. here it is utilized further in that specific code. in a complete system this could be count booking or generate ids etc.
### requisition_id = 10000 + 1
Line 1:- this line will create a simple, hardcoded requisition id. it adds 1 with 10000 every time, thus giving 1000a. in real use this id would normally be dynamic or auto increment.
### print(f"\n printing booking information")
\n prints before it adds a blank line. you are searching for data as of October 2021
### print(f"date:{date}")
Shows word date and then the date the user entered so far
### print(f"staff id:{staff id}")
this prints the staff id. NOTE: There is a typo in staff id in the attacjment, it the attachment, it should be staff id
### print(f"staff name:{staff name}")
prints the name that the user previously entered.
### print("requisition id: {}"'format(requisition id))
shows the static requisition id 10001
### staff info()
this line seems to call a function called staff infor(). but in the code you supplied there isn't actually a def satff info(): line that wraps the other lines. if this is present, the above code should be inside a function as follows: def staff info():
### all code goes here
if you are running your script directly, then you can just remove staff info() line.
Example output enter date: 2025-04-18 staff id: ST123 staff name:Alice
printing booking information date: 2025-04-18 staff id : ST123 staff name: Alice requisition id:10001
## How to run this script
1 whta you do is save the code in file staff info py
2 install python if you do not already have it.
3 the first step is to open a terminal or command prompt.
4 run the file using
## python staff info.py
possible improvements correct the typo in staff id - must be staff id increment the requisition id with each call export the data add a menu or a loop to handle multiple entires 
## summary
this is a small but potentially useful example of how to use input () python storing values in variables printing user-friendly output.

