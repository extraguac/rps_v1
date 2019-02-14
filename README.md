# rps_v1
Rock Paper Scissors

print("Welcome to the great game of Rock Paper Scissors!")
print("Here is the rule.\nPlayer 1 enters his/her choice.\nPlayer 2 enters his/her choice.\n")

p1 = input("Player 1, please enter your choice: ").lower()
p2 = input("Player 2, please enter your choice: ").lower()


if p1 == "rock" or "paper" or "scissors" and p2 == "rock" or "paper" or "scissors":
	if p1 == p2:
		print("It's a tie!")
	elif p1 == "rock":
		if p2 == "paper":
			print("Player 2 wins!")
		else:
			print("Player 1 wins!")
	elif p1 == "paper":
		if p2 =="scissors":
			print("Player 2 wins!")
		else:
			print("Player 1 wins!")
	elif p1 == "scissors":
		if p2 == "rock":
			print("Player 2 wins!")
		else:
			print("Player 1 wins!")	
else:
	print("Please type correct choices!")
