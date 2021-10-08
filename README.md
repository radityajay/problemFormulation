# HW 2  Problem Formulation

## Question:

You have a 9 × 9 grid of squares, each of which can be colored red or blue. The grid is initially colored all blue, but you can change the color of any square any number of times. Imagining the grid divided into nine 3 × 3 sub-squares, you want each sub-square to be all one color but neighboring sub-squares to be different colors.

a. Formulate this problem in the straightforward way. Compute the size of the state space.

b. Given the goal, we need consider only colorings where each sub-square is uniformly colored. Reformulate the problem and compute the size of the state space.

c. How many solutions does this problem have?

## Answer:

Start state

<img src="Images/start.png" width="200px">

Sub Kotak

<img src="Images/sub-kotak.png" width="200px">

Goal State

<img src="Images/goalState.png" width="200px">

A. Size untuk state space awal adalah 81

B. 9x9 kotak dibagi menjadi sub kotak 3x3 maka menjadi 9 bagian.

C. Goal state ini memerlukan 5 sub kotak untuk mencapai goal state karena merubah dari start state warnanya biru semua menjadi 5 sub kotak berubah menjadi merah.