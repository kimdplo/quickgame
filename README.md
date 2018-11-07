# quickgame
Quick text based game
#short text adventure game 

import random
import time
import textwrap



def displayIntro():
    print('----------------------The Earth Castle-------------------------------------------\n')

    print("The winter has lasted longer than it should have. Your village is starving.")
    time.sleep(2)
    print("There is a legend that says; 'Should the winter see no end, find the Earth Orb and burn it. The "
          "sun and leaves will then be as it once was.'\n")
    time.sleep(3)
    ch = input('What is your name? >> ')

    print('Hello, ' + (ch) + (". You are the chosen one. You must travel to the Castle and find the Earth Orb.\n"))
    time.sleep(3)
    print("So, you set out on your own to find the Castle. You have been traveling for several months before you finally\n"
          "stumble upon the steps of the Earth Castle. You look up and see two doors before you. The door on the left\n"
          "is labeled 'Bonjour' and the door on the right 'Au revoir'.\n")

#example of loop
def choosePath():
    path = ''
    while path != 'a' and path != 'b':
        path = input("Please choose a door, Au revoir (a)  or Bonjour (b): >> ")
    if path in  ['b', 'B']:
        print("You chose the door labeled Bonjour. You will now roll the dice to see if you are successful.")
        time.sleep(2)

    else:
        print('You open the door labeled Au revoir. ')
        return

def rollDice():
    rollDice = [1, 2, 3, 4]
    dice = input("Pick a number 1 through 4 to to learn if you encounter the Troll or find the Earth Orb.>>  ")
    wile



def checkPath(choosenPath):
    print("You open a door.")
    print('the orb is in the big room')
    correctPath = random.randint (1,2)
def startgame():
   for x in range(1):
       print(random.randint(1,10))
       if x <= 5:
           print('You open the door labeled Au revoir. Behind this door lives the Earth Castle troll. He comes out and '
                 'bops you on the head. Your village must now \nchoose another savior!')
       else:
           print("You enter the castle. It's very dark inside. You find the orb and save the village!")

displayIntro()

choosePath()
time.sleep(4)
startgame()
time.sleep(2)
print('\n')
print(">>>>>>>>>>>THANKS FOR PLAYING<<<<<<<<<<<")
