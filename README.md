# Game-rock-paper-scissor-import random

print("welcome to the game")
choices = ["rock", "paper", "scissors"]
user = input("Enter your choice (rock, paper, scissors): ")
computer = random.choice(choices)
print(f"Computer chose {computer}.")

if user == computer:
    print("It's a tie!")
elif (user == "rock" and computer == "scissors") or \
     (user == "paper" and computer == "rock") or \
     (user == "scissors" and computer == "paper"):  
    print("You win!")
else:
    print("Computer wins!")

