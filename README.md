# Game
Rock-Paper-Scissors is a simple two-player game where, at a signal, players make figures with their hands, representing a rock, a piece of paper, or a pair of scissors. The winner is determined according to a set of rules. You can find the official rules under the Resources.   
Befor you continue, ensure you have installed the latest version of anaconda  for python
Anaconda is configure with IDEs like jupyter notebook and spyder
Install Jupyter for python on ananconda

Open jupyter and create a new file

Type in code in workspace
choices = ["rock","paper","scissors"]
This are the set of choices for both players to pick from. This is a game played between two players
    computer = random.choice(choices)
   Both player choices are unknown to each other
   
   Winner is determined by this Set of Rules
  if player == computer:
        print("computer: ",computer)
        print("player: ",player)
        print("Tie!")
when a player makes the same hand figure or choose same figure as the computer, they get a tie

    elif player == "rock":
        if computer == "paper":
            print("computer: ", computer)
            print("player: ", player)
            print("You lose!")
   Else when a player chooses a rock and computer a paper,the computer loses because a rock could crush a paper
   
        if computer == "scissors":
            print("computer: ", computer)
            print("player: ", player)
            print("You win!")
when a computer chooses a scissors, it loses because a rock can be used to crush the scissors

    elif player == "scissors":
        if computer == "rock":
            print("computer: ", computer)
            print("player: ", player)
            print("You lose!")
   Else a player chooses a scissors and computer a rock,,the player lose
        if computer == "paper":
            print("computer: ", computer)
            print("player: ", player)
            print("You win!")
when the computer then pick a paper, it becomes the winner because scissors can be used to cut a paper

    elif player == "paper":
        if computer == "scissors":
            print("computer: ", computer)
            print("player: ", player)
            print("You lose!")
   Else a player picks a paper and computer picks a scissors,,, in this case the computer becomes the winner
   
        if computer == "rock":
            print("computer: ", computer)
            print("player: ", player)
            print("You win!")
  when a computer picks a rock, the computer becomes the winner
  
When you are done, click run to run the code
