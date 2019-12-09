main.py
import random # imports random ability
question = input("Do you want to know the future my child? (Yes/No) ")
#Prompts Person if they want to know their fortune
if question == "no":
	jesus = input(" Are you sure? ") 
	if jesus == "no":
		print("Shoo, bad child")
	elif jesus == "yes": 
  # line 8: RNG to choose one of 6 fortunes    
		yeet = random.randrange(6) + 1
    if yeet == "6":
      print("YOU HAVE A GREAT REGRET, JUST LET IT GO")
    elif yeet == "5":
      print("THERE ARE MANY FUTURES AHEAD OF YOU: \n JESUS WILL FORGIVE YOU \n JESUS WILL NOT FORGIVE YOU")
    elif yeet == "4":
      print("JOE WUZ HERE")
    elif yeet == "3":
      print(" LIFE IS UNFAIR, DEAL WITH IT ")
    elif yeet == "2":
      print("The watermelon god will bestow great gifts upon you")
	elif yeet == "1":
			print("You are a lost cause child")
else
	name = input(" What is your name my child? ")
	if name.startswith('a'):
		print("Joe wuz here") 
    # Joe had been there
	elif name.startswith('b') or name.startswith('c'):
    print("You will get a new friend on a blue moon")
	elif name.lower().startswith('i'):
		print(' JESUS CHRIST IS OUR LORD AND SAVIOR BELIEVE IN HIM ')
	elif name.lower().startswith('j') or name.lower()startswith('k') or name.lower()startswith('m'):
		print('what is your reddit username?????????????????????????????')
  	elif name.lower().startswith("d"):
    	print("SAINT JOE IS GOD")
  	elif name.lower().startswith("e"):
    	Image.open(urlopen(https://i.imgur.com/rTvfFWZ.gif))
	elif name.startswith('z'):
		print ("When you are of the age of 248 yoy will be wronged and you will sin")
	else:
		print ("You have no future")
	# Makes fortunes with if, elif and else statements
