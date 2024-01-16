# RailroadInk-like Game

Digital game made using C++ based on the game [RailroadInk board game](https://www.amazon.com.br/Railroad-Vermelho-Gal%C3%A1pagos-Jogos-Diversos/dp/B07Y2QKZBN) & [Railroad Ink Challenge on Steam](https://store.steampowered.com/app/1592740/Railroad_Ink_Challenge/). 
This project is a study and it's not aimed to make any profits.

## Game rules
A game of Railroad Ink is played over 7 rounds. The goal is to connect as many Exits to each other as possible by drawing Routes that can create Networks. The more Exits  you connect to the same Network, the more points it will be worth. Bonus points can be earned for your Longest Railway, your Longest Highway, and by drawing on the Central Spaces of your Board.

### Game Play
At the beginning of each round, you'll get 4 possible Routes to place on your board.
There are a few placing rules you need to follow:

1. Each Route you place must be connected by at least one side to either one of the Exits  or a preexisting Route. If you can't connect a Route, you can't place it.
2. You must place all 4 Routes shown on the dice each round (if possible, and each Route showing can only be placed once, of course).
3. You can't place Routes in a way that directly connects Railways to Highways or vice versa (you need a Station to do that).
4. You can place one Special Route per round and you can only place 4 of them along the 7 rounds 

### Routes and Special Routes

Routes:

![image](https://github.com/doniniramos/railroad-like-game/assets/31694530/afb2369a-0dc6-4f53-85ca-77fd631c5cad)
![image](https://github.com/doniniramos/railroad-like-game/assets/31694530/03e6e7d4-e9e1-43fb-be33-79ffa6b9cbb4)

Special Routes:

![image](https://github.com/doniniramos/railroad-like-game/assets/31694530/79ff2dfe-22e4-4806-81ba-0455be65e25c)

### Scoring

#### Connecting Exits

Connecting Exits  is the main way to score points in Railroad Ink. At the end of the game, each set of Exits that are connected to each other via the same Network of Routes is worth a number of points determined by the number of Exits connected together, as shown on the Network Values on your Board.

![image](https://github.com/doniniramos/railroad-like-game/assets/31694530/5b0e29c6-bcf2-469e-9433-8acb610b81e2)

> Note 1: Overpasses only allow you to make two of your Networks cross each other, but they don't create a connection between the two.
> Note 2: You can use Stations to connect Railway Routes and Highway Routes to each other.

#### Longest Highway
Longest Highway is the longest unbroken streak of adjacent spaces where you drew Highway Routes that are connected to each other (not counting any loops or branches), such as the route marked in blue to the right. You score 1 point for each space that makes up your single longest Highway branch. Stations do not interrupt your Highway.

#### Longest Railway
Longest Railway is determined the same way as the Longest Highway,, only counting Railway Routes instead of Highway Routes, like the one marked in red to the right (worth 5 points).

#### Central Spaces
Central Spaces are the 9 spaces in the middle of your board. You score 1 point for each Central Space you drew anything on.

> If you have two Longest Routes (with the same number of spaces), only 1 counts towards your final score.
