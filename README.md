# Girly Chaos - Chess game

## 📨 Subject and report
Given by Jules FOUCHY : https://julesfouchy.github.io/Learn--Clean-Code-With-Cpp/sujet/

## 🎪 Chess Game
Let yourself be carried away for a wild game of chess with some unusual rules ! <br>

List of special rules:
- Crazy Bishop : When the player wants to move the bishop, randomness can cause it to change trajectory. The Poisson distribution that generates the random variable. Controlled frequency, independent events.
- Glitter Bombshell : Just like creepers in Minecraft: the closer a piece gets to the enemy line, the greater its chance of exploding and eliminating the pieces around it (1 square). Exponential law with a threshold x calculated each turn and summed.
- Slay or Nay : Every 5 turns, the player has a 1-in-2 chance that their turn will pass. Count system. Uniform distribution and binomial distribution: 2 possible choices
- Angry Knight : The knight can only move in an L-shape: it wants to wipe out everything. The rule is uniform: if a piece is within its range, there’s a probability it will capture it.There are 8 possible moves, each with a probability of ⅛, but the probability that it will move to a specific spot varies depending on the board

## Results

<img width="2017" height="647" alt="Girly Chaos(1)" src="https://github.com/user-attachments/assets/1350a0ad-a488-44fd-aeb0-f5cccf58901b" />
<img width="6319" height="3000" alt="image(1)" src="https://github.com/user-attachments/assets/d2313e01-ff1a-40a1-abe2-65ff725d5831" />
