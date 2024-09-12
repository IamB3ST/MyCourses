# Game Theory
## Chapter 1 Game Theory Intro
### Self-interested Agents and Utility Theory
An agent is **self-interested** mean that agent has its own description of states of the world. And each such agent has  a utility function which represents their potential responses for the impact of uncertainty.
### Defining Games
The **Players** of the Game are decision makers. And the **Actions** in the Game are things that players can do.
There are two standard representations of Games:
- Normal Form, which lists what payoffs get as a function of their actions.
- Extensive Form, which includes timing of moves.
#### The Normal Form
Assuming we have $n$-person normal form: $<N,A,u>$:
- Players: $N = \{1,...,n\}$ is a finite set, indexed by $i$
- Actions for player is $A_i$, and the action profile is $a=(a_1,a_2,...,a_n) \in A=A_1\times...\times A_n$.
- Utility function for player $i$: $u_i: A\to R$. And $u=(u_1,...,u_n)$ is a profile of utility functions.
#### The Standard Matrix Representation
We could write a 2-player game as a matrix: "row" player is player 1, and "column" player is player  2.
### Kinds of Games
#### Pure Competition Games
In pure competition games, for all action profile, the sum of payoffs is a constant number. Special case: zero sum.
#### Cooperation Games
Players have exactly the same interests. There is no conflict: all players want the same things. And they always get the sam payoffs
#### General Games
The most interesting games combine elements of **cooperation** and **competition**. The sum of the payoffs are always positive and players will never get "fail". They just competite for limited payoffs.
### Nash Equilibrium Intro
Nash Equilibrium refers a situation where each player in a game is assumed to know the equilibrium strategies of the other players, and no player has anything to gain by changing their own strategy.

And if you know what everyone else was going to do, it would be easy to pick your **Best Response**.
Let $a_{-i}=<a_1,…,a_{i-1},a_{i+1},…,a_n>$
now $a=(a_{-1},a_i)$
Your Best Response could be definite as:
$a\*_i \in BR(a_{-i}) iff \forall a_i \in A_i, u_i(a\*_i,a_{-i}) \geqq u_i(a_i,a_{-i})$
Then the Nash Equilibrium could be definite as:
$a=<a_1,…,a_n>$ is a (”pure strategy”)Nash Equilibrium if $\forall i,a_i \in BR(a_{-i})$
  
### Dominant Strategies
Let $s_i$ and $s’_i$ be two strategies for player $i$, and let $S_{-i}$ be the set of all possible strategy profiles for the other players.

Definition:
$s_i$ strictly dominates $s’_i$ if $\forall s_{-i} \in S_{-i},u_i(s_i,s_{-i}) > u_i(s’_i,s_{-i})$
$s_i$ very weakly dominates $s’_i$ if $\forall s_{-i} \in S_{-i},u_i(s_i,s_{-i}) \geqq u_i(s’_i,s_{-i})$

If one strategy dominates all others, we say it is **dominant**.

### Analyzing Games
Previous notes, we only talk about the Best Response of an Agent. Sometimes, one outcome $o$ is at least as good for every agent as another outcome $o’$, and there is some agent who strictly prefers $o$ to $o’$. We say that $o$ Pareto-dominates $o’$. An outcome $o*$ is **Pareto-Optimal** if there is no other outcome that Pareto-dominates it.



