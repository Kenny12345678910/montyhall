# montyhall
'''
Created on Nov 15, 2018

@author: klevin21
'''
from random import randint
car = randint(1, 3)
guess= int(input("Which door would you like to pick:"))
print("the car was behind Door#",car,"!")
print("You picked Door #",guess,".")
if car==1 and guess==1:
    print("There is a goat behind Door number #2")
choice=input("Would you like to change your pick?")
if choice==("yes"):
    guess=3
else car==2 and guess==2:
    print("There is a goat behind Door number #2")
choice=input("Would you like to change your pick?")
if choice==("yes"):
    guess=3
