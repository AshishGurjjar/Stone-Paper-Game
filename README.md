# Stone-Paper-Game
Just for fun
import random
user = int(input("please enter 0 for stone,1 for paper,2 for scissor:"))
comp = random.randint(0,2)
print(comp)
if (user==0 and comp==0):
  print("Draw")
elif ( user==0 and comp==1):
  print("comp win")
elif ( user==0 and comp==2):
  print("user win")
elif ( user==1 and comp==1):
  print("Draw")
elif ( user==1 and comp==0):
  print("user win")
elif ( user==1 and comp==2):
  print("comp win")
elif ( user==2 and comp==0):
  print("comp win")
elif ( user==2 and comp==1):
  print("user win")
elif ( user==2 and comp==2):
  print("draw")
