# Random-number
Random number in py
# guess the number game in Python by CodeSpeedy.com
import random
random_number = random.randint(1,20)
win = False
Turns =0
while win==False:
    Your_guess = input("Enter a number between 1 and 20")
    Turns +=1
    if random_number==int(Your_guess):
        print("You won!")
        print("Number of turns you have used: ",Turns)
        win == True
        break
    else:
     if random_number>int(Your_guess):
        print("Your Guess was low, Please enter a higher number")
     else:
        print("your guess was high, please enter a lower number")
