# Parking  Lot Project

# About the project
This project is all about the parking the cars in slots
# To design a parking lot system with ability to find:
* Registration numbers of all car with color. 
* slot number where a car is parked
* This code is done with the python 03

## Functions
* We can create a parking lot with n number of slots
* We can park the car
* Leave from the slot
* Check the status
## How to run? 
This code can be run in two modes
* Interactive 
* File mode: It can also run by accepting the file which is containing inputs. 

## Interactive mode
To choose Interactive mode just we need to type ' Interactive '. So that it will ask you the input
### Commands to get an output
We can use the following commands in Interactive mode to geet an out.

* create_parking_lot < NUMBER OF SLOTS > It will create the parking slot with no.of required slots.

Example: create_parking_lot 4

* park < REGISTRATION NUMBER > < COLOR > It will park the particular car

Example: park KA-01-MM-0002 Red

* leave < SLOT NUMBER> It will remove the car from that slot & the output will be 'slot number 4 free'

example: leave 4

* status It will give the current status of parking lot. 

For example this is the sample  output when there is no slots 

allocated "status"

Slot No. || Registration No || Colour"

# File mode
It accepts a filename as a parameter at the terminal and read the commands from the file.

 The file inputs are followed below

 create_parking_lot 6

park KA-01-HH-1234 White

park KA-01-HH-9999 White

park KA-01-BB-0001 Black

park KA-01-HH-7777 Red

park KA-01-HH-2701 Blue

park KA-01-HH-3141 Black

leave 4

status

park KA-01-P-333 White

park DL-12-AA-9999 White

registration_numbers_for_cars_with_colour White

slot_numbers_for_cars_with_colour White

slot_number_for_registration_number KA-01-HH-3141

slot_number_for_registration_number MH-04-AY-1111

# Done by charan_gudivada  


