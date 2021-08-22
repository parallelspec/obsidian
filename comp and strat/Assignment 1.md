<h1>Assignment 1</h1> 

<h4>Philip Phung 1046504</h4>

<h3>Question 1</h3> 

a) ![[Pasted image 20210822172021.png]] 
This is the game tree associated with this game.

b) Player 1 has 2 pure strategies, and player 2 has 2. 

c) The SPNE here is $\{b, ba\}$. That is, player 1 chooses to veto $b$, then player 2 at that information node chooses $a$, resulting in a pay-off of $(2,1)$. See the attached diagram below:

![[Pasted image 20210822172206.png]]

d) No. This can be shown via a game table associated with this game: 
$$\begin{pmatrix}  
X & 1,2 & 0,0\\  
\color{red}{2,1} & X & 0,0\\
2,1 & 1,2 & X
\end{pmatrix}$$
The first row depicts Player 1 vetoing $a$, and so on. The columns depict player 2 choosing the remaining two options. $X$ means that this option is not possible for player 2 to choose as player 1 as vetoed that option during their turn. For example, $(1,2)$ in the first row is the payoff associated with player 1 vetoing $a$, and player 2 choosing $b$. 

We can use cell-by-cell inspection to work out that the only NE payoff is $(2,1)$ in the first column, second row, highlighted in red. This is also the SPNE. 

<h3>Question 2</h3> 

a) The SPNE is $\{d, d\}$. The payoff associated is $(6, 4)$. 
![[Pasted image 20210822172513.png]]
b) Player A does have first-mover advantage, as the SPNE has their highest payoff possible of $6$, whilst also forcing player B to select that strategy $(d, d)$ as it has the highest pay-off out of the two options at that node for them. 

c) Player B does not have second-mover advantage, as the SPNE does not have their highest payoff possible, $6$, nor do they have any 'leverage' here to force A potential modification to make B have second-mover advantage would be to change $(6,4)$ to $(6, 6)$ and change $(3, 5)$ to $(1337, 5)$. Player A would ideally like to achieve that new pay-off of $1337$ by choosing to go up first, but player B would choose to go down instead, resulting in a pay off of $(3, 6)$. ![[withspne1.png]]

d) $$\begin{pmatrix}  
\space& uu & ud & du & dd \\  
u & 3,5 & 3,6 &  \\
\end{pmatrix}$$
where $(3,5)$ is the payoff when both players choose to go up. The other NE to the game are: