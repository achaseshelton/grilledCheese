# **Making a Grilled Cheese Sandwich**

### **Deconstruct and Identify**

User wants to make a grilled cheese sandwich for lunch.

- Users turns on the stove.
- USeer puts a pan on the stove.
- User spreads butter on bread if none is on the bread already.
- User puts bread butter side down in the pan.
- User places slices of cheese on the bread in the pan.
- User spreads butter on the 2nd piece of bread if none is already on the bread.
- User puts 2nd slice of bread on top of the cheese butter side up.
- If the 1st slice of bread has cooked long enough, User flips bread to the uncooked side.
- If the 2nd slice of bread has cooked long enough, User takes the bread out of pan and puts it on a plate.
- User cuts the grilled cheese in half.

### **Objects/Data Structures**

- Oven
    - Set Temperature button
    - Changes the temperature with an onPress functon.
- Pan
- Bread
    - Does bread have butter?
    - 2 Slices, Bread1 and Bread2
- Butter
- Cheese


## **Pseudocode**

### START

//Begin Program

INIT()

stove onPress(stoveTemperature)

if(pan < 1)
    
    User.placesPan(onStove)

if(butter.onBread1 < 1)

    function spreadButter(Bread1)

User.placesInPan(Bread1)

User.placesOnBread1(Cheese)

if(butter.onBread2 < 1)

    function spreadButter(Bread2)

User.placesOnCheese(bread2)

if(bread1 = cooked)

    function flipSandwich()

if(bread2 = cooked)

    User.placesOnPlate(grilledCheese)

function sliceSandwich

//End Program

### **Functions & Objects**

- INIT
    - CREATE Stove
    - CREATE Pan
    - CREATE Bread1
    - Create Bread2
    - Create Butter
    - Create User
    - Create Plate
- onPress
    - Sets temperature of stove to entered value.
- spreadButter
    - Spreads needed amount of butter
- flipSandwich
    - Flips the sandwich to the other side.
- sliceSandwich
    - Slies the sandwich in half.

- User
    - placesPan
    - placesInPan
    - placesOnBread1
    - PlacesOnCheese
    - placesOnPlate