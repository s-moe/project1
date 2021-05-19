# project1
Project title: 
"Pizza Delivery" is a game/story hybrid that helps you learn the importance of keeping your tank full of gas and getting a customer's order correct.

# Win State:
Get $100 in tips (amount to be determined).
Or deliver all of the pizzas without getting fired.

# Lose State:
Run out of gas or get fired for delivering the wrong pizza too many times (3 warnings gets you fired).

# Classes(do I need them for this?): 
- Driver/Car
- Customer - customer will tip the driver if they receive the correct pizza
    
# Buttons: 
- Drive (decreases amount of fuel by random number); 
- Deliver (matches pizza ordered with pizza delivered) - if they match you get a tip, if they don't match up you get a warning; 
- Refuel (adds fuel to the car and reduces your tip amount); 
- Quit (quits the game); 
- Reset (Resets the game);

# Display: 
- Tip amount: $ ; 
- Fuel gauge: (miles left in tank)
- Pizzas left to deliver: 

# Basic premise: 
- There will be an array of pizzas ordered.
- There will be an array of pizzas to be delivered.
- When the driver delivers a pizza it will randomly choose a pizza from the delivered array and see if it matches the pizza from the ordered array.
- If the pizzas match, the customer tips the driver by a random amount; if they don't match the driver gets a warning. 3 warnings and you are fired.
- Delivering a pizza also removes that pizza from the delivered pizzas array.
- The fuel tank will reduce by a random amount.
- The fuel tank will increase by a certain amount and it will also reduce the tip amount by $10. If the driver doesn't have enough money to pay for fuel s/he has to keep delivering pizzas to try to get tipped so s/he can refuel. 
- If the driver delivers all of the pizzas without getting fired or makes $100 in tips s/he wins.
- If the driver runs out of fuel or gets 3 warnings s/he loses. 

