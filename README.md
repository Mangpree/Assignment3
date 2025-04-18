# Assignment3
## Script (Python) to Get Staff Requisition Info
It is a basic Python script which prompts the user for a few fields to get some basic staff booking information, generates a requistion ID, and prints the results in a nicely formatted way.

This is also a good beginner project that will help someone that's learning how to use user input, variables, and print statements in Python.
## What This Script Does
### Takes user input for:
	Date of the request
	Staff ID
	Staff name
### Delivers a “basic” requisition ID
### Outputs all gathered information to the display
For this you could use a simple internal system in which employees request services or resources and then get confirmation that their entry was received.
## Code Explanation, Line by Line
### python
### date = input ("Enter date: ")
This line prompts the user for the date (in the form of "2025-04-18").
Anything the user types, the variable date saves.

### staff_id = input("staff_id : ")
This prompts the user for their staff ID (format "ST123").
The variable staff_id stores the input.

### staff_name = input("staff_name:")
This prompts the user to enter their name.
Set var staff_name to entered name.

### counter = 1
That initializes a variable counter to be 1.
Here it is not utilized further in that specific code. In a complete system this could be count bookings or generate ids etc.

### requisition_id = 10000 + 1
Line 1 : This line will create a simple, hardcoded requisition ID.
It adds 1 with 10000 every time, thus giving 10001.
In real use this ID would normally be dynamic/auto-increment.

### print(f"\n printing booking information")
\n prints before it adds a blank line.
You are searching for data as of October 2021.

### print(f"date:{date}")
Shows word date and then the date the user entered so far

### print(f"stsff_id:{staff_id}")
This prints the staff ID.
NOTE: There is a typo in "stsff_id" in the attachment, it should be "staff_id".

### print(f"staff_name:{staff_name}")
Prints the name that the user previously entered.

### print("requisition_id: {}".format(requisition_id))
Shows the static requisition ID (10001).

### staff_info()
Note: This line seems to call a function called staff_info().
But in the code you supplied there isn’t actually a def staff_info(): line that wraps the other lines.
If this line is present, the above code should be inside a function as follows:
def staff_info():
## all the code goes here
If you are running your script directly, then you can just remove staff_info() line.

Example Output
Enter date: 2025-04-18
staff_id: ST123
staff_name: Alice

Printing booking information
date: 2025-04-18
stsff_id: ST123
staff_name: Alice
requisition_id: 10001

## How to Run This Script
1.	What you do is save the code in file staff_info py
2.	Install Python if you do not already have it.
3.	The first step is to open a terminal or command prompt.
4.	Run the file using:
   
## python staff_info.py
Possible Improvements
Correct the typo in stsff_id → must be staff_id
Increment the requisition ID with each call (instead of fixing it at 10001)
Export the data (to file CSV or text)
Ensure that the date format is valid (e.g., YYYY-MM-DD)
Add a menu or a loop to handle multiple entries

## Summary
This is a small but potentially useful example of:
How to use input() Python
Storing values in variables
Printing user-friendly output


