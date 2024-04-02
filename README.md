# carp
import random

def fishing():#star of function definition
    num = random.randrange(0,100)
    if (num < 33):
        print("you caught a carp")
        return "carp"
    elif (num < 66):
        print("you caught a woodskip")
        return "woodskip"
    else:
        print("you caught a catfish")
        return "catfish"
    #add more if staments
    
print(fishing(), "added to your inventory!")

