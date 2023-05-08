Download Link: https://assignmentchef.com/product/solved-the-game-of-nim
<br>
5/5 - (3 votes)

This is a well-known game with a number of variants. The following variant has an interesting winning strategy. Two players alternately take marbles from a pile. In each move, a player chooses how many marbles to take. The player must take at least one but at most half of the marbles. Then the other player takes a turn. The player who takes the last marble loses.



Write a program in which the computer plays against a human opponent. Generate a random integer between 10 and 100 to denote the initial size of the pile. Generate a random integer between 0 and 1 to decide whether the computer or the human takes the first turn. Generate a random integer between 0 and 1 to decide whether the computer plays smart or stupid. In stupid mode the computer simply takes a random legal value (between 1 and n / 2) from the pile whenever it has a turn. In smart mode the computer takes off enough marbles to make the size of the pile a power of two minus 1—that is, 3, 7, 15, 31, or 63. That is always a legal move, except when the size of the pile is currently one less than a power of two. In that case, the computer makes a random legal move.

You will note that the computer cannot be beaten in smart mode when it has the first move, unless the pile size happens to be 15, 31, or 63. Of course, a human player who has the first turn and knows the winning strategy can win against the computer. Below is an example of a game run:

Example Output:

Current number of marbles in pile: 95

Computer removes 12 marble(s).

Current number of marbles in pile: 83

How many marbles do you want to remove: 12

Current number of marbles in pile: 71

Computer removes 17 marble(s).

Current number of marbles in pile: 54

How many marbles do you want to remove: 20

Current number of marbles in pile: 34

Computer removes 6 marble(s).

Current number of marbles in pile: 28

How many marbles do you want to remove: 28

How many marbles do you want to remove: 25

How many marbles do you want to remove: 20

How many marbles do you want to remove: 12

Current number of marbles in pile: 16

Computer removes 4 marble(s).

Current number of marbles in pile: 12

How many marbles do you want to remove: 12

How many marbles do you want to remove: 4

Current number of marbles in pile: 8

Computer removes 4 marble(s).

Current number of marbles in pile: 4

How many marbles do you want to remove: 6

How many marbles do you want to remove: 3

How many marbles do you want to remove: 2

Current number of marbles in pile: 2

Computer removes 1 marble(s).

Current number of marbles in pile: 1

How many marbles do you want to remove: 1