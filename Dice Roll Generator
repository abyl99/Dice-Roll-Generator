import random

#Enter the minimum and maximum limits of the dice rolls below

min_val = 1

max_val = 6

#The variable that stores the game's default setting, user will select to play or not


#The dice roll loop if the user wants to continue

while True:
    
    print("Welcome to the game! Please make a selection")
    
    roll_again = input("Do you want to roll the dice?")
    
    print()
    
    if roll_again == "yes" or roll_again == "y" or roll_again == "YES" or roll_again == "Y":

        print("Dices rolling...")
        
        print("The values are :")

        #Printing the randomly generated variable of the first dice

        print(random.randint(min_val, max_val))

        #Printing the randomly generated variable of the second dice

        print(random.randint(min_val, max_val))        

    #The game will end if the user does not want to continue
    
    elif roll_again == "no" or roll_again == "n" or roll_again == "NO" or roll_again == "N":
        
        print("Thank you for playing")
        
        print()
        
    #If player chooses anything other than "y" or "n", ask the player to try again
    else: 
        
        print("Try again")
        
        print()
