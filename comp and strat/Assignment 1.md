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
u & 3,5 & 3,5 & \color{red}3,6 & \color{red}3,6  \\
d & 1,1 & \color{red}6,4 & 1,1 & \color{lime}6,4
\end{pmatrix}$$
where the rows are player 1's strategies, and the columns player 2's strategies. The NEs (which are not SPNE) are $\{u, du\}, \{u, dd\}$ and $\{d, ud\}$, highlighted in red. These are not SPNE as player A would always elect to choose $d$ knowing that player B would always select $d$ in the following node, meaning it isn't logical for the rest of the NEs to be rationally feasible to occur in play.

e) One modification would be to change the payoff $(3, 6)$ to $(6, 6)$. This means the players are indifferent in deciding between strategies $(u, d)$ and $(d, d)$, making them both SPNEs.  

<h3>Question 3</h3>  

a) This is an imperfect information game, as PW will always have uncertainty if he and VD decide to drive fast regardless of VD's intial choice to upgrade his car or not. (10% chance of both crashing, but only PW will be affected). 

b) ![[Pasted image 20210822182041.png]] Assuming PW knows about the initial upgrade.

c) Assuming PW knows about this initial upgrade: 
SPNE: $\{uf, f\}$, where $u$ is upgrade and $f$ is fast. PW should always choose to go fast, as expected payoffs of going fast are $0.1(0) + 0.9(500) = 450$, compared to the potential $100$ by choosing to go slow at those certain nodes. They are highlighted below:

![[Pasted image 20210822184022.png]]

For VD's case, if he upgrades his car then he should still always go fast, as the expected payoff if PW goes fast as well is $0.1(3500) + 0.9(500) = 800$, more than if he went slow. 

Even if he does not upgrade his car, then he should still go fast. The expected payoff for this strategy $(NF,F)$ is $0.1(0) + 0.9(500) = 450$, higher than if VD went slow. This is not the SPNE for this case, as $450 < 800$, and I am assuming that $R$ is a different payoff metric than $C$.


