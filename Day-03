print(r'''
                     _              
                    | |             
 _ __   _____      _| |_ ___  _ __  
| '_ \ / _ \ \ /\ / / __/ _ \| '_ \ 
| | | |  __/\ V  V /| || (_) | | | |
|_| |_|\___| \_/\_/  \__\___/|_| |_|
                                          
                                                       
''')
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.")
move = input("Where do you want to go? Left or Right: ").lower()
if move == "left":
    move = input("Do you want to Swim or Wait? ").lower()
    if move == "wait":
        move = input("Which door? Red or Yellow or Blue: ").lower()
        if move == "red":
            print("Burned by fire.\nGame Over.")
        elif move == "yellow":
            print("You Win!")
        elif move == "blue":
            print("Eaten by beasts.\nGame Over.")
        else:
            print("Game Over.")
    else:
        print("Attacked by trout.\nGame Over.")
else:
    print("Fall into a hole.\nGame Over.")
