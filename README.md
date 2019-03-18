![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Statistics Foundations

## Challenge 1
One player rolls two dices. Describe the measure space and the random variable for:
* A. The numbers he/she obtains
* B. The sum of the rolls
* C. Take only the maximum value

Describe the following events:
* For case A: the number is greater than 5
* Case B: The sum is even
* Case C: the maximum is the value of both rolls
omega: {1,2,3,4,5,6}
str={(1,1),(1,2),(1,3),...}
A: X (5,6) = 5,6
B: X (5,5) = 10
C: X ()
## Challenge 2
One player is taking two cards from poker deck. Describe the measure space and the random variable for:
* A. The number of figures he takes.
* B. The sum of the cards (figures sum 10 and ace sum 15)
* C. The number of hearts or spades he takes.

Describe the 3 following events:
* For case A. The number of figures is two.
* Case B: The sum is 17.
* Case C: The number is less than 8.
omega: {Ace,2,3,4,5,6,7,8,9,10, Jack, Queen, King}*{hearts,clubs, pikes, diamonds}
str={(Ace hearts, 5 pikes),(10 clubs, king clubs),...}
A: X (Queen hearts, King spades) = 2
B: X (Queen hearts, King clubs) = 20
C: X (10 spades, king clubs) = 1

## Challenge 3
Two players roll a dice. Describe the measure space and the random variable for:
* The score for player A
* Greatest score
* Earnings of player A with the rule “the player that has the greatest score receives a coin for the other player”
* Earnings of the player A with the rule “the player that has the greatest score receives the difference between the two scores”

Describe the events:
* The score of player A is 2 (case A)
* The greatest punctuation is <=2 (case B)
* If the winner pays the other the difference (case C):
  * A wins at least 4 coins.
  * A loses more than 2 coins.
  * No one loses.
omega: {1,2,3,4,5,6}
str={(1,1),(1,2),(1,3),...}
A: X(2,5) = 2
B: X(1,2) = 2, X (1,1)= 1
C1: X(5,3),(6,2),(6,5),(2,1)
X(1,4),(5,6)
X(3,3)
C2: X (5,1)
X(2,5)
X(4,4)

## Challenge 4
Three players take balls. There are red, blue, green and black balls. They can take three balls at most with the following rules:
* If the ball is red they can’t take another ball.
* If the ball is green they earn a point and they can take another ball.
* If the ball is blue they can take another ball.
* If the ball is black one point is removed and they can’t take another ball.

Describe the measure space and the random variable for:
* Player A wins (no tie).
* Player A and B get the same points.
* All players get 0 points.
A: X(green,red,black)
B: X(green, (blue,green), red)
C: X(red,(blue,red),red)

## Challenge 5
Now we are four players. What changes for each case?
A: X(green,red,black,red)
B: X(green, (blue,green), red,black)
C: X(red,(blue,red),red,red)

## Challenge 6
We have 5 balls in an urn, two black and three white. Describe the measure space and the random variable for:
* The number of white balls after 3 takes, if every time we take a ball we keep it.
* The number of white balls after 3 takes, if every time we take a ball we put it again into the urn.
* The number of black balls after 3 takes, if every time we take a ball we keep it.
* The number of black balls after 3 takes, if every time we take a ball we put it again into the urn.
omega: {white,black}
A: X(b,b,w)=1 (w,w,w)=3 (w,w,b)=2
B: X(b,b,w)=1 (w,w,w)=3 (w,w,b)=2 (b,b,b)=0
C: X(b,b,w)=2 (w,w,w)=0 (w,w,b)=1
D: X(b,b,w)=2 (w,w,w)=0 (w,w,b)=1 (b,b,b)=3
