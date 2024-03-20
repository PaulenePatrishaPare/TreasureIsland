print('''
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\` . "-._ /_______________|_______
|                   | |o;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/_____ /
*******************************************************************************
''')
print("Welcome to Trisha's Treasure Island.")
print("Your mission is to find the treasure.\n\n") 


choice1 = input("\nYou\'re at a crossroad. Where do you want to go? Type 'left' or 'right'\n").lower() 

if choice1 == "left":
  choice2 = input("\nYou have arrived at a lake. Would you like to swim or wait? Type 'swim' or 'wait'\n").lower() 
  if choice2 == "wait": 
    choice3 = input("\nYou come across a three doors, which color door do you choose to open? Type 'red', 'blue', or 'yellow'\n").lower()
    if choice3 == "red" or choice3 == "blue":
      print("\nGame Over.")
    if choice3 == "yellow":
      print("\nYou Win! You found the treasure, which is me hehe")
  else:
    print("\nGame Over. Wrong answer. A whale ate you.")
else:
  print("\nGame Over. Wrong answer. You fell in a hole.") 
