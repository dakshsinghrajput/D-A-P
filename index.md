```python
print("hello world of D-A-P")
import random
#here you can se code of some unique game which are two player
print("You can play the two player games available here")
print("Number Game")
while True:
    a=random.randrange(0,9)
    P1=int(input("enter any number that you think computer have chossen you are player 1"))
    if(P1==a):
        print("Player1 pricited computers number",a)
        break
    P1=int(input("enter any number that you think computer have chossen you are player 2"))
    if(P1==a):
        print("Player2 pricited computers number",a)
        break
    elif(P1==P2):
        print("")
