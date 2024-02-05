import random

user_wins = 0
computer_wins = 0
options = ["rock" , "paper" , 'scissors']

while True:
	user_input = input("Choose Rock/Paper/Scissors or Q to quite the game: ").lower()
	if user_input == "q":
		break

	if user_input not in options:
			continue

	random_number = random.randint(0,2)
	# Rock: 0 , Paper: 1 , Scissors: 2
	computer_pick = options[random_number]
	print('Computer picked', computer_pick + '.')

	if user_input == 'rock' and computer_pick == "scissors":
		print ('You Won!')
		user_wins += 1

	elif user_input == 'paper' and computer_pick == "rock":
		print ('You Won!')
		user_wins += 1
		
	elif user_input == 'scissors' and computer_pick == "paper":
		print ('You Won!')
		user_wins += 1
		
	else: 
		print("you lost!")
		computer_wins += 1

	print(f'Score is  YOU {user_wins} : {computer_wins} COMP')


print(f'You won {user_wins} times.')
print(f'The computer won {computer_wins} times.')

print('GoodBye :)')


