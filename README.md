![image](https://user-images.githubusercontent.com/95454600/178151584-55f0d2ca-fd9c-44ed-bcf2-39d7bf1fabba.png)

# Monty Hall Problem
### This is a project to create a game that proves the Monty Hall Problem in a funny way

## Motivations
### For a long time I've been trying to explain this problem to some friends, but it is something hard to accept for those who haven't studied statistics beyond high school. I've tried playing with them using frosted cups, but this way we have a limitation on how many times we can play it. In a computer, we can run it how many times we want and easly see the results.

## Technology
- Python;
- VS Code.

## Services
- Github.

## Python Libraries
- Numpy;
- re (regex);
- random.

## How to use
You will see two files, the game (project001_open-TMH.ipynb) and the "tester" (project001-TMH-Test.ipynb).

### The game is really simple and has seven steps:

1- show the initial interface with the 3 doors to the user;


2- the computer secretly and randomly select a door to set the prize;

3- asks the user to select a door (1/2/3), the program will only accept this three options as input;

![image](https://user-images.githubusercontent.com/95454600/178150667-42ce541f-d7d7-407b-ae87-7c1815b32079.png)

4- the game will open an empty door and show the door selected by the user (P), the empty door ( ) and the "other" door (1/2/3);

5- the game will ask if the user want to change his option to the "other" door, it will only accept yes (y) or no (n) as input;

![image](https://user-images.githubusercontent.com/95454600/178150815-a6a626f4-50f8-4de3-80e3-2acd6308152b.png)

6- then the three doors will open and show the prize (*). A board with the results will appear showing the total games played, total games played changing doors, win percentage when changing doors, total games played while not changing doors and win percentage while not changing doors;

![image](https://user-images.githubusercontent.com/95454600/178151253-e04a4743-08b5-48c8-88dd-264c0742e06b.png)


7- finally, the game will ask the user if he wants to play again, only accepting yes (y) or no (n) as input.


### The tester is simpler and will ask how many times the user wants to run the game, then it will randomly choose the inputs and show the results:

![image](https://user-images.githubusercontent.com/95454600/178151305-f181f6ba-a6e4-45d1-86d7-3eb70f1e38d8.png)


## Conclusion
With the game (and the tester) is easy to see that the Monty Hall Problem really works. When you run the tests multiple times, the win percentage when changing doors converges to approximately 66.66% and the win percentage while not changing doors converges to approximately 33.33%.

## Links
https://en.wikipedia.org/wiki/Monty_Hall_problem

## Versions
1.0

## Author
Matheus Reali de Oliveira Fabricio (https://github.com/MatheusReali/MatheusReali)
