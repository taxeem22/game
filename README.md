print('''*******************************************************************************
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
/______/______/______/______/______/______/______/______/______/______/[TomekK]
*******************************************************************************''')
print("welcome to treasure island")
print("your mission is to find the treasure")
choice1 = input("you are at a cross road where do you want to go? \ntype 'left' or 'right'\n")
if choice1 == "left":
    choice2 = input("you have come to the lake there is an island in the middle of the lake type wait to wait for boat or type swim to cross the lake ")
    if choice2 == "wait":
        print("boat is commimg and it will take you to the lake and finally u have reached to the island unharmed")
    elif choice2 == "swim":
        print("you have to cross the lake throgh swimming and finally u have reached the island harmed ")
    else:
        print("you have choosen the door that does not exist..")
    choice3 = input("there is a house in the island having 2 doors in it  one is red another is yellow which door do you choose? ") 
    if choice3 == "red":
        choice4 = input("you have entered into a new room having two doors one is green another is blue which one do you choose? ")
        if choice4 == " blue":
            print("game over u have choosen a wrong door ")
        elif choice4 == "green":
            print("you dont find treasure but found some antique pieces better luck next time..")
        else:
            print("you choose the door that does not exist")
    elif choice3 == "yellow":
        print("congratulations you have found the treasure.. best of luck ")
else:
    print("game over u have choosen a wrong path best of luck for a next time")
        
        
        
        
        
    
    
    
