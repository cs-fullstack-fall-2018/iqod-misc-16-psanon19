# IQOD_Misc_16_a

## DO EVERYTHING MANUALLY

Given an input of a multi-dimensional array, create a program that will print a list of car parts that will fit on a shelf 10 units long.

The first item inside of an element in the multi-dimensional array is the car part name, and the second item is the number of units it takes up.

Print ```Shelf 1: [CAR PART]``` then list the car parts that will fit on each shelf. If multiple car parts fit on the shelf make sure they all print on one line. Once the maximum is reached, move to shelf 2, etc. You CANNOT go over 10 units or it won't fit.

Use the array below for testing. It should work for any length of array with the name/unit specifications:
```
carParts = [
["Door",10],
["Window",6],
["Electrical supply system",4],
["Ignition electronic system",4],
["Car seat",5],
["Braking system",2],
["Exhaust system",1],
["Suspension and steering systems",3],
["Transmission system",2],
["Air conditioning system (A/C)",3],
["Bearings",3],
["Hose",7]
]
```

Example:
```
carParts = [
["radio",8],
["windshield wiper",6],
["tire pressure gauge",3]]

iqod13(carParts)
```
Output
```
Shelf 1: radio
Shelf 2: windshield wiper, tire pressure gauge
```
