---
title: Probability — Questions and Solutions
tags:
  - probability
  - practice
  - solutions
---

# Probability — Questions and Solutions

> [!note]
> **Obsidian math:** Inline equations use `$...$`; display equations use `$$...$$`.
>
> Each problem below contains the **complete question first**, followed immediately by its solution.


---

# 1. Question

Give examples for the following cases. For each of them, explain the sample space and the events properly.

Only assigning numerical values satisfying the conditions will not suffice.

**(a)** \(P(A \cap B) > P(A)P(B)\) [2 marks]

**(b)** \(P(A \cap B) < P(A)P(B)\) [2 marks]

### Solution
Consider the experiment of rolling a fair die once.

Sample space:


$$
\Omega=\{1,2,3,4,5,6\}
$$


Let


$$
A=\{2,4,6\}
$$


be the event that the result is even, and


$$
B=\{4,5,6\}
$$


be the event that the result is greater than 3.

Then


$$
P(A)=\frac{3}{6}=\frac12,
\qquad
P(B)=\frac{3}{6}=\frac12.
$$


Their intersection is


$$
A\cap B=\{4,6\},
$$


so


$$
P(A\cap B)=\frac{2}{6}=\frac13.
$$


But


$$
P(A)P(B)=\frac12\cdot\frac12=\frac14.
$$


Therefore


$$
\boxed{P(A\cap B)=\frac13>\frac14=P(A)P(B)}.
$$


The events are positively associated: knowing that the die result is greater than 3 makes an even result more likely.


### (b) $P(A\cap B)<P(A)P(B)$


### Solution
Again roll a fair die once.


$$
\Omega=\{1,2,3,4,5,6\}.
$$


Let


$$
A=\{1,2,3\}
$$


be the event that the result is at most 3, and


$$
B=\{3,4,5,6\}
$$


be the event that the result is at least 3.

Then


$$
P(A)=\frac12,\qquad P(B)=\frac46=\frac23.
$$


The intersection is


$$
A\cap B=\{3\},
$$


so


$$
P(A\cap B)=\frac16.
$$


Meanwhile,


$$
P(A)P(B)=\frac12\cdot\frac23=\frac13.
$$


Hence


$$
\boxed{P(A\cap B)=\frac16<\frac13=P(A)P(B)}.
$$


---


---

# 2. Question

Alice and Bob are among a group of eight college students who are interested in debating. Three students are picked randomly from this group to represent the college at an intercollegiate fest. Let \(A\) be the event that Alice is among those picked, and \(B\) denote the event that Bob is among those picked.

**(a)** \(P(A)\) [1 mark]

**(b)** \(P(A \mid B)\) [1 mark]

**(c)** \(P(A \cup B)\) [1 mark]

### Solution
There are


$$
\binom83
$$


possible groups.

For Alice to be selected, choose the remaining 2 students from the other 7:


$$
\binom72.
$$


Therefore


$$
P(A)=\frac{\binom72}{\binom83}
=\frac{21}{56}
=\boxed{\frac38}.
$$


### (b) Find $P(A\mid B)$


### Solution
Given that Bob has already been selected, we need to choose the remaining 2 students from the other 7 students.

The probability that Alice is among those two is


$$
P(A\mid B)=\frac{\binom61}{\binom72}
=\frac{6}{21}
=\boxed{\frac27}.
$$


Equivalently,


$$
P(A\mid B)=\frac{P(A\cap B)}{P(B)}.
$$


### (c) Find $P(A\cup B)$


### Solution
Use the addition rule:


$$
P(A\cup B)=P(A)+P(B)-P(A\cap B).
$$


By symmetry,


$$
P(A)=P(B)=\frac38.
$$


For both Alice and Bob to be selected, choose one more student from the remaining 6:


$$
P(A\cap B)=\frac{\binom61}{\binom83}
=\frac6{56}
=\frac3{28}.
$$


Therefore


$$
P(A\cup B)
=\frac38+\frac38-\frac3{28}
=\boxed{\frac{9}{14}}.
$$


---


---

# 3. Question

You flip a fair coin thrice and note the outcome (in \(\{H,T\}^3\)). Define the following events.

\(A\) is the event that all tosses have the same result (all H or all T).

\(B\) is the event that you see at least one H and at least one T.

\(C\) is the event that you see at most one H.

**(a)** Are events \(A\) and \(B\) independent? [1 mark]

**(b)** Are events \(B\) and \(C\) independent? [1 mark]

**(c)** Are events \(A\) and \(C\) independent? [1 mark]

### Solution
$$
A\cap B=\varnothing
$$


because an outcome cannot have all tosses equal and also contain both H and T.

Therefore


$$
P(A\cap B)=0.
$$


But


$$
P(A)=\frac28=\frac14,
\qquad
P(B)=\frac68=\frac34.
$$


Hence


$$
P(A)P(B)=\frac14\cdot\frac34=\frac3{16}\neq0.
$$


Therefore


$$
\boxed{A\text{ and }B\text{ are not independent}.}
$$


### (b) Are $B$ and $C$ independent?


### Solution
$$
B\cap C=\{HTT,THT,TTH\}.
$$


Thus


$$
P(B\cap C)=\frac38.
$$


Also,


$$
P(B)=\frac34,\qquad P(C)=\frac48=\frac12.
$$


So


$$
P(B)P(C)=\frac34\cdot\frac12=\frac38.
$$


Therefore


$$
\boxed{B\text{ and }C\text{ are independent}.}
$$


### (c) Are $A$ and $C$ independent?


### Solution
$$
A\cap C=\{TTT\}.
$$


Therefore


$$
P(A\cap C)=\frac18.
$$


Also,


$$
P(A)P(C)=\frac14\cdot\frac12=\frac18.
$$


Hence


$$
\boxed{A\text{ and }C\text{ are independent}.}
$$


---


---

# 4. Question

Show that if two events \(A\) and \(B\) are independent, then \(A^c\) and \(B^c\) are also independent. [2 marks]

### Solution
Given that $A$ and $B$ are independent,


$$
P(A\cap B)=P(A)P(B).
$$


We need to show


$$
P(A^c\cap B^c)=P(A^c)P(B^c).
$$


By De Morgan's law,


$$
A^c\cap B^c=(A\cup B)^c.
$$


Thus


$$
P(A^c\cap B^c)
=1-P(A\cup B).
$$


Using the addition rule,


$$
=1-[P(A)+P(B)-P(A\cap B)].
$$


Using independence,


$$
=1-P(A)-P(B)+P(A)P(B).
$$


Factor:


$$
=(1-P(A))(1-P(B)).
$$


Therefore


$$
P(A^c\cap B^c)=P(A^c)P(B^c).
$$


Hence


$$
\boxed{A^c\text{ and }B^c\text{ are independent}.}
$$


---


---

# 5. Question

Consider a knockout tournament with \(k\) rounds of matches including the final. Recall that in each round, half of the remaining players are ‘knocked out’ of the tournament. For example, the grand slam tennis tournaments start with 128 players and have seven rounds of matches. Define a suitable sample space for the random outcome of the tournament. Each element of this sample space need not be equally likely.

### Solution
After $k$ rounds, the initial number of players is


$$
2^k.
$$


A convenient sample space is the set of all possible **tournament brackets/outcomes**, where an outcome records the winner of every match in every round.

For example, for $k=2$, there are 4 players:


$$
\{1,2,3,4\}.
$$


A possible outcome can be represented by


$$
((1\text{ beats }2),(3\text{ beats }4),(1\text{ beats }3)).
$$


Thus an element of the sample space specifies:

1. the winner of every first-round match,
2. the winner of every second-round match,
3. and so on until the final.

More formally,


$$
\boxed{\Omega=\{\text{all complete assignments of winners to every match in the tournament}\}.}
$$


This is preferable to taking only the identity of the champion, because different match histories can lead to the same champion.

If players have unequal strengths, these complete outcomes need not be equally likely.


---


---

# 6. Question

A course is taught by four instructors. Before every lecture, the instructors draw lots and one of them is randomly chosen to teach on that day. What is the probability that in \(N\) classes, all the lecturers would have taught at least once. Generalise to \(k\) instructors teaching the course.

### Solution
Use inclusion-exclusion.

Let $A_i$ be the event that instructor $i$ is **never** selected.

We want


$$
P(A_1^c\cap A_2^c\cap A_3^c\cap A_4^c).
$$


For a particular set of $j$ instructors to be absent, every class must be taught by one of the remaining $4-j$ instructors.

Therefore


$$
P(A_{i_1}\cap\cdots\cap A_{i_j})
=
\left(\frac{4-j}{4}\right)^N.
$$


There are $\binom4j$ ways to choose those $j$ instructors.

Hence inclusion-exclusion gives


$$
\boxed{
P(\text{all 4 teach})
=
\sum_{j=0}^{4}
(-1)^j
\binom4j
\left(\frac{4-j}{4}\right)^N
}.
$$


Expanded:


$$
\boxed{
1
-4\left(\frac34\right)^N
+6\left(\frac12\right)^N
-4\left(\frac14\right)^N
}.
$$


The general result for $k$ instructors is


$$
\boxed{
P(\text{all }k\text{ teach})
=
\sum_{j=0}^{k}
(-1)^j
\binom{k}{j}
\left(\frac{k-j}{k}\right)^N
}.
$$


This is also


$$
\frac{k!\,S(N,k)}{k^N},
$$


where $S(N,k)$ is a Stirling number of the second kind.


---


---

# 7. Question

Numbers 1, 2, 3, 4, 5, and 6 are randomly placed on a circle. What is the probability that they are placed in increasing order?

### Solution
Treat clockwise and counterclockwise directions as fixed.

There are $6!$ assignments to six fixed positions.

For the numbers to occur in increasing clockwise order, the arrangement must be a cyclic rotation of


$$
1,2,3,4,5,6.
$$


There are 6 such rotations.

Therefore


$$
P=\frac{6}{6!}
=\frac{1}{5!}
=\boxed{\frac1{120}}.
$$


Equivalently, if rotations of a circular arrangement are considered identical, there are $5!$ circular arrangements and only one is increasing.


---


---

# 8. Question

A and B play the following game of dice. Both roll a die once. A gets is assigned the number obtained on its roll. If B rolls a number other than one, it is assigned whatever it rolls. However, if B rolls a one, then it rolls again and will be assigned whatever it rolls the second time (even if it rolls a one). Whoever is assigned the highest value wins. If there is a tie A wins. What is the probability that A wins the game.

### Solution
Let $B$ denote B's final assigned value.

For $B=1$, the first roll must be 1 and the second roll must be 1:


$$
P(B=1)=\frac16\cdot\frac16=\frac1{36}.
$$


For $b=2,3,\ldots,6$, B can obtain $b$:

- directly on the first roll, probability $1/6$;
- or first roll 1 and second roll $b$, probability $1/36$.

Thus


$$
P(B=b)=\frac16+\frac1{36}=\frac7{36},
\qquad b=2,\ldots,6.
$$


A wins if $A>B$. Therefore


$$
P(A\text{ wins})
=
\sum_{a=1}^6P(A=a)P(B<a).
$$


Now


$$
P(B<a)
=
\frac1{36}+(a-2)\frac7{36}
$$


for $a\ge2$.

Hence


$$
P(A\text{ wins})
=
\frac16
\left[
0+\frac1{36}
+\frac8{36}
+\frac{15}{36}
+\frac{22}{36}
+\frac{29}{36}
\right].
$$


So


$$
P(A\text{ wins})
=
\frac16\cdot\frac{75}{36}
=
\boxed{\frac{25}{72}}.
$$


---


---

# 9. Question

There are \(n\) urns and the \(r\)-th urn contains \((r-1)\) brown balls and \((n-r)\) black balls. You pick an urn at random and pick two balls at random without replacement. What is the probability that the second ball is black. What is the conditional probability that the second ball is black given that the first ball is black.

### Solution
For urn $r$, the total number of balls is


$$
(r-1)+(n-r)=n-1.
$$


There are $n-r$ black balls.

### 1. Probability the second ball is black

By symmetry, conditional on the chosen urn,


$$
P(B_2\mid r)=\frac{n-r}{n-1}.
$$


Average over the $n$ urns:


$$
P(B_2)
=
\frac1n\sum_{r=1}^n\frac{n-r}{n-1}.
$$


Since


$$
\sum_{r=1}^n(n-r)=\frac{n(n-1)}2,
$$


we obtain


$$
P(B_2)
=
\frac1n\cdot
\frac{n(n-1)/2}{n-1}
=
\boxed{\frac12}.
$$


### 2. Conditional probability

For $n\ge4$, given the first ball is black, the probability that the second is also black, conditional on urn $r$, is


$$
P(B_2\mid B_1,r)
=
\frac{n-r-1}{n-2}.
$$


It is easier to calculate using the joint probability:


$$
P(B_1\cap B_2)
=
\frac1n
\sum_{r=1}^n
\frac{(n-r)(n-r-1)}{(n-1)(n-2)}.
$$


Using


$$
\sum_{j=0}^{n-1}j(j-1)
=
\frac{n(n-1)(n-2)}3,
$$


we get


$$
P(B_1\cap B_2)=\frac13.
$$


Since $P(B_1)=1/2$,


$$
P(B_2\mid B_1)
=
\frac{P(B_1\cap B_2)}{P(B_1)}
=
\frac{1/3}{1/2}
=
\boxed{\frac23}.
$$


So


$$
\boxed{P(B_2)=\frac12,\qquad P(B_2\mid B_1)=\frac23}.
$$


---


---

# 10. Question

I choose a number uniformly in the range \([1,1000000]\). Using inclusion exclusion principle, determine the probability that the chosen number is divisible by one or more of 4, 6, and 9.

### Solution
Let

- $A$: divisible by 4
- $B$: divisible by 6
- $C$: divisible by 9.

Using inclusion-exclusion:


$$
P(A\cup B\cup C)
=
P(A)+P(B)+P(C)
-P(A\cap B)-P(A\cap C)-P(B\cap C)
+P(A\cap B\cap C).
$$


The relevant LCMs are


$$
\operatorname{lcm}(4,6)=12,
$$


$$
\operatorname{lcm}(4,9)=36,
$$


$$
\operatorname{lcm}(6,9)=18,
$$


$$
\operatorname{lcm}(4,6,9)=36.
$$


Because $1{,}000{,}000$ is not necessarily a multiple of all these numbers, one can count exactly using floors:


$$
\begin{aligned}
N
={}&
\left\lfloor\frac{10^6}{4}\right\rfloor
+\left\lfloor\frac{10^6}{6}\right\rfloor
+\left\lfloor\frac{10^6}{9}\right\rfloor\\
&-\left\lfloor\frac{10^6}{12}\right\rfloor
-\left\lfloor\frac{10^6}{36}\right\rfloor
-\left\lfloor\frac{10^6}{18}\right\rfloor\\
&+\left\lfloor\frac{10^6}{36}\right\rfloor.
\end{aligned}
$$


The two $36$-terms cancel.

Since


$$
\left\lfloor\frac{10^6}{4}\right\rfloor=250000,
$$


$$
\left\lfloor\frac{10^6}{6}\right\rfloor=166666,
$$


$$
\left\lfloor\frac{10^6}{9}\right\rfloor=111111,
$$


$$
\left\lfloor\frac{10^6}{12}\right\rfloor=83333,
$$


$$
\left\lfloor\frac{10^6}{18}\right\rfloor=55555,
$$


we get


$$
N=388889.
$$


Therefore


$$
\boxed{
P=\frac{388889}{1{,}000{,}000}
\approx0.388889
}.
$$


> **Important:** Using $1/4,1/6,1/9$ directly gives the limiting/idealized value $7/18$, but the exact answer for $1,\ldots,1{,}000{,}000$ uses floor counts.


---


---

# 11. Question

An urn starts off with one black and one brown ball. Sample one ball from this urn and put the ball back into the urn along with another ball of the same color. Now there are three balls in the urn. Repeat this action \(N\) times, i.e., sample a ball and put the ball and another ball of the same color back into the urn. There are now \((N+2)\) balls in the urn. Find the probability that there \(k\) black balls are in the urn.

### Solution
After $N$ additions, the number of black balls can be


$$
k=1,2,\ldots,N+1.
$$


This is the classical **Polya urn** model with initial counts $1,1$.

A key property is that the distribution of the final number of black balls is uniform.

Therefore


$$
\boxed{
P(K=k)=\frac1{N+1},
\qquad k=1,\ldots,N+1.
}
$$


### Why is it uniform?

Suppose exactly $k-1$ of the $N$ additions were black and $N-(k-1)$ were brown.

Every particular color sequence with these counts has the same probability


$$
\frac{1\cdot2\cdots k-1\cdot1\cdot2\cdots(N-k+1)}
{2\cdot3\cdots(N+1)}
=
\frac{(k-1)!(N-k+1)!}{(N+1)!}.
$$


There are


$$
\binom{N}{k-1}
=
\frac{N!}{(k-1)!(N-k+1)!}
$$


such sequences.

Multiplying,


$$
P(K=k)
=
\binom{N}{k-1}
\frac{(k-1)!(N-k+1)!}{(N+1)!}
=
\frac1{N+1}.
$$


---


---

# 12. Question

Consider a best-of-five tennis match in which whoever wins three sets first wins the match. The players are evenly matched, i.e., each one wins a set with equal probability. Find the probability that loser has won \(k\) sets.

### Solution
The loser can win only


$$
k=0,1,2
$$


sets.

If the loser wins $k$ sets, the match lasts


$$
k+3
$$


sets, because the winner must get the third win on the final set.

The final set must be won by the eventual winner.

Among the first $k+2$ sets, the loser must have won exactly $k$, so the number of possible sequences is


$$
\binom{k+2}{k}.
$$


Each complete sequence has probability


$$
\left(\frac12\right)^{k+3}.
$$


Therefore


$$
\boxed{
P(K=k)
=
\binom{k+2}{k}\frac1{2^{k+3}},
\qquad k=0,1,2.
}
$$


Thus:

### $k=0$


$$
P(K=0)=\frac18.
$$


### $k=1$


$$
P(K=1)=\binom31\frac1{16}
=\frac3{16}.
$$


### $k=2$


$$
P(K=2)=\binom42\frac1{32}
=\frac3{16}.
$$


So


$$
\boxed{
P(K=0)=\frac18,\quad
P(K=1)=\frac3{16},\quad
P(K=2)=\frac3{16}.
}
$$


The sum is $1/2$, as expected: these probabilities describe one specified player being the loser.


---


---

# 13. Question

A coin is tossed independently \(n\) times. The probability of heads at each toss is \(p\). At each time \(k\) (\(k=2,3,\ldots,n\)), we get a reward if \(k\)-th toss was a head and the previous toss was a tail. Let \(A_k\) be the event that a reward is obtained at time \(k\).

**(a)** Are events \(A_k\) and \(A_{k+1}\) independent?

**(b)** Are events \(A_k\) and \(A_{k+2}\) independent?

Justify all answers.

### Solution
We have


$$
A_k=\{T_{k-1},H_k\}
$$


and


$$
A_{k+1}=\{T_k,H_{k+1}\}.
$$


For both to occur, toss $k$ would have to be both H and T.

Therefore


$$
A_k\cap A_{k+1}=\varnothing.
$$


Hence


$$
P(A_k\cap A_{k+1})=0.
$$


But


$$
P(A_k)=P(A_{k+1})=(1-p)p.
$$


Thus


$$
P(A_k)P(A_{k+1})=p^2(1-p)^2.
$$


For $0<p<1$, this is positive, so


$$
\boxed{A_k\text{ and }A_{k+1}\text{ are not independent}.}
$$


### (b) Are $A_k$ and $A_{k+2}$ independent?


### Solution
We have


$$
A_k=\{T_{k-1},H_k\}
$$


and


$$
A_{k+2}=\{T_{k+1},H_{k+2}\}.
$$


These events involve disjoint tosses, so independence of the individual tosses implies independence of the events.

Directly,


$$
P(A_k\cap A_{k+2})
=
(1-p)p(1-p)p
=
p^2(1-p)^2.
$$


Also,


$$
P(A_k)P(A_{k+2})
=
[p(1-p)]^2
=
p^2(1-p)^2.
$$


Therefore


$$
\boxed{A_k\text{ and }A_{k+2}\text{ are independent}.}
$$


---


---

# 14. Question

There are three types of coins which have different probabilities of landing heads when tossed.

- Type A coins are fair, with probability 0.5 of heads
- Type B coins are biased and have probability 0.7 of heads
- Type C coins are biased and have probability 0.9 of heads

Suppose I have a drawer containing 5 coins: 2 of type A, 2 of type B, and 1 of type C. I reach into the drawer and pick a coin at random. Without showing you the coin I flip it once and get heads. What is the probability it is Type A? Type B? Type C?

### Solution
The prior probabilities are


$$
P(A)=\frac25,\qquad
P(B)=\frac25,\qquad
P(C)=\frac15.
$$


Using Bayes' theorem:


$$
P(A\mid H)
=
\frac{P(H\mid A)P(A)}{P(H)}.
$$


First find $P(H)$:


$$
P(H)
=
0.5\cdot\frac25
+0.7\cdot\frac25
+0.9\cdot\frac15.
$$


Therefore


$$
P(H)=0.2+0.28+0.18=0.66.
$$


### Type A


$$
P(A\mid H)=\frac{0.5(0.4)}{0.66}
=\boxed{\frac{10}{33}}.
$$


### Type B


$$
P(B\mid H)=\frac{0.7(0.4)}{0.66}
=\boxed{\frac{14}{33}}.
$$


### Type C


$$
P(C\mid H)=\frac{0.9(0.2)}{0.66}
=\boxed{\frac9{33}=\frac3{11}}.
$$


Check:


$$
\frac{10}{33}+\frac{14}{33}+\frac9{33}=1.
$$


---


---

# 15. Question

Prove that

**(a)** \(P(A \cap B) \ge P(A) + P(B) - 1\)

**(b)** \(P(A_1 \cap A_2 \cap \cdots \cap A_n) \ge P(A_1) + P(A_2) + \cdots + P(A_n) - (n-1)\)

### Solution
Using the addition rule,


$$
P(A\cup B)
=
P(A)+P(B)-P(A\cap B).
$$


Since probabilities cannot exceed 1,


$$
P(A\cup B)\le1.
$$


Therefore


$$
P(A)+P(B)-P(A\cap B)\le1.
$$


Rearranging,


$$
\boxed{
P(A\cap B)\ge P(A)+P(B)-1
}.
$$


### (b) Prove


$$
P(A_1\cap\cdots\cap A_n)
\ge
\sum_{i=1}^nP(A_i)-(n-1).
$$



### Solution
Use complements:


$$
(A_1\cap\cdots\cap A_n)^c
=
A_1^c\cup\cdots\cup A_n^c.
$$


By the union bound,


$$
P(A_1^c\cup\cdots\cup A_n^c)
\le
\sum_{i=1}^nP(A_i^c).
$$


Thus


$$
1-P(A_1\cap\cdots\cap A_n)
\le
\sum_{i=1}^n[1-P(A_i)].
$$


So


$$
1-P(\cap_i A_i)
\le
n-\sum_iP(A_i).
$$


Hence


$$
\boxed{
P(A_1\cap\cdots\cap A_n)
\ge
\sum_{i=1}^nP(A_i)-(n-1)
}.
$$


---


---

# 16. Question

Consider two events \(A\) and \(B\) such that \(P(A) > 1-\delta\), and \(P(B) > 1-\delta\), for very small \(\delta>0\). Prove that \(P(A\cap B)\) is close to 1.

### Solution
From Question 15,


$$
P(A\cap B)\ge P(A)+P(B)-1.
$$


Using the assumptions,


$$
P(A\cap B)
>
(1-\delta)+(1-\delta)-1.
$$


Therefore


$$
\boxed{
P(A\cap B)>1-2\delta.
}
$$


Thus, when $\delta$ is very small, the intersection probability is very close to 1.

Equivalently,


$$
P((A\cap B)^c)<2\delta.
$$


---


---

# 17. Question

The Erdos-Rényi model \(G(n,p)\) is a simple random graph model, where \(n\) is the number of nodes in the graph. In a social networking context, each node might represent a person. Every pair of nodes is connected by an edge with probability \(p\). The occurrence of each edge in the graph is independent of other edges in the graph.

Let \(B_n\) be the event that a graph randomly generated according to the \(G(n,p)\) model has at least one isolated node. We want to show that

\[
P(B_n) \le n(1-p)^{n-1}
\]

and conclude that for any \(\epsilon>0\), if

\[
p=p_n=(1+\epsilon)\frac{\ln(n)}{n},
\]

then

\[
\lim_{n\to\infty}P(B_n)=0.
\]

### Solution
Let $I_i$ be the event that node $i$ is isolated.

Node $i$ has $n-1$ possible edges incident to it.

For it to be isolated, all $n-1$ edges must be absent.

Since edges are independent,


$$
P(I_i)=(1-p)^{n-1}.
$$


Now


$$
B_n=\bigcup_{i=1}^n I_i.
$$


By the union bound,


$$
P(B_n)
\le
\sum_{i=1}^nP(I_i)
=
n(1-p)^{n-1}.
$$


Hence


$$
\boxed{P(B_n)\le n(1-p)^{n-1}}.
$$


Now set


$$
p=p_n=(1+\epsilon)\frac{\ln n}{n}.
$$


Using


$$
1-x\le e^{-x},
$$


we obtain


$$
P(B_n)
\le
n\exp[-p_n(n-1)].
$$


Therefore


$$
P(B_n)
\le
n\exp\left[
-(1+\epsilon)\frac{n-1}{n}\ln n
\right].
$$


Rewrite:


$$
P(B_n)
\le
n^{1-(1+\epsilon)(n-1)/n}.
$$


As $n\to\infty$,


$$
1-(1+\epsilon)\frac{n-1}{n}
\longrightarrow
-\epsilon.
$$


Thus the upper bound behaves like


$$
n^{-\epsilon}\to0.
$$


Since probabilities are nonnegative,


$$
0\le P(B_n)\le n^{-\epsilon+o(1)}\to0.
$$


Hence


$$
\boxed{\lim_{n\to\infty}P(B_n)=0}.
$$


---


---

# 18. Question

Each pack of Gold Cookies contains a coupon. There are \(n\) types of coupons available, and each is independent of previously obtained coupons. The probability of getting \(i\)-th coupon is \(p_i\), with \(\sum p_i=1\). Let \(A_i\) denote the event that you have at least one coupon of type \(i\) in the \(k\) already obtained coupons. Answer the following (assume \(i\ne j\)):

**(a)** \(P(A_i)\)

**(b)** \(P(A_i \cup A_j)\)

**(c)** \(P(A_i \mid A_j)\)

### Solution
The complement $A_i^c$ means none of the $k$ coupons is type $i$.

For one coupon,


$$
P(\text{not type }i)=1-p_i.
$$


By independence,


$$
P(A_i^c)=(1-p_i)^k.
$$


Therefore


$$
\boxed{
P(A_i)=1-(1-p_i)^k
}.
$$


### (b) Find $P(A_i\cup A_j)$


### Solution
The complement is the event that neither type $i$ nor type $j$ appears.

For one coupon,


$$
P(\text{neither }i\text{ nor }j)
=
1-p_i-p_j.
$$


Therefore


$$
P((A_i\cup A_j)^c)
=
(1-p_i-p_j)^k.
$$


Hence


$$
\boxed{
P(A_i\cup A_j)
=
1-(1-p_i-p_j)^k
}.
$$


### (c) Find $P(A_i\mid A_j)$


### Solution
First,


$$
P(A_i\cap A_j)
=
1-P(A_i^c)-P(A_j^c)+P(A_i^c\cap A_j^c).
$$


Therefore


$$
P(A_i\cap A_j)
=
1-(1-p_i)^k-(1-p_j)^k+(1-p_i-p_j)^k.
$$


Also,


$$
P(A_j)=1-(1-p_j)^k.
$$


Thus


$$
\boxed{
P(A_i\mid A_j)
=
\frac{
1-(1-p_i)^k-(1-p_j)^k+(1-p_i-p_j)^k
}{
1-(1-p_j)^k
}
}.
$$


---


---

# 19. Question

You are a contestant in a TV show. There are 3 doors leading to rooms of which 2 are empty and 1 contains a Mercedes. You are asked to choose one room and a correct guess will win you the Mercedes. After you select a room, the game master opens one of the doors of another room that you did not select and also that does not contain the Mercedes.

Prove that you will improve your chance to win the Mercedes if you change your choice from the initial guess to the remaining closed door.

Mathematically:

- \(E_1\): Event of winning the Mercedes with the initial guess
- \(E_2\): Event of winning the Mercedes if he changes his initial guess
- \(C\): Event where you know one of the rooms not containing the Mercedes

Prove that \(P(E_1) < P(E_2 \mid C)\).

### Solution
Suppose you initially choose Door 1.

There are three equally likely possibilities:

| Mercedes location | Initial choice wins? | Switching wins? |
|---|---:|---:|
| Door 1 | Yes | No |
| Door 2 | No | Yes |
| Door 3 | No | Yes |

Therefore


$$
P(E_1)=\frac13.
$$


The initial choice has probability $1/3$ of being correct.

Consequently, it has probability


$$
1-\frac13=\frac23
$$


of being wrong.

If the initial choice is wrong, the host is forced to open the only other empty door. The remaining closed door must contain the Mercedes.

Thus switching wins whenever the initial choice was wrong:


$$
P(E_2\mid C)=\frac23.
$$


Therefore


$$
\boxed{
P(E_1)=\frac13<\frac23=P(E_2\mid C)
}.
$$


The key point is that the host's action is **not random among all doors**: the host deliberately avoids the Mercedes.


---


---

# 20. Question

A group of \(n\) men enter a restaurant and check their hats. The hat-checker is absent minded, and upon leaving, she redistributes the hats back to the men at random. What is the probability \(P_n\) that no man gets his correct hat, and how does \(P_n\) behave as \(n\) approaches infinity?

### Solution
There are


$$
n!
$$


possible assignments of hats.

Let $A_i$ be the event that person $i$ receives their own hat.

We want


$$
P_n=P\left(\bigcap_{i=1}^nA_i^c\right).
$$


By inclusion-exclusion,


$$
P_n
=
1-\binom n1\frac1{n!/(n-1)!}
+\binom n2\frac1{n!/(n-2)!}
-\cdots.
$$


More simply, the number of permutations with no fixed points is the number of **derangements**:


$$
!n
=
n!\sum_{k=0}^n\frac{(-1)^k}{k!}.
$$


Hence


$$
\boxed{
P_n
=
\frac{!n}{n!}
=
\sum_{k=0}^n\frac{(-1)^k}{k!}
}.
$$


As $n\to\infty$,


$$
\sum_{k=0}^{\infty}\frac{(-1)^k}{k!}
=e^{-1}.
$$


Therefore


$$
\boxed{
\lim_{n\to\infty}P_n=\frac1e
}.
$$


---


---

# 21. Question

You are given that at least one of the events \(A_n\), \(1\le n\le N\), will occur almost surely i.e.

\[
P\left(\bigcup_{n=1}^N A_n\right)=1.
\]

Also no more than two occur almost surely. If \(P(A_n)=p\) and \(P(A_n\cap A_m)=q\), \(m\ne n\), then show that

\[
p\ge\frac1N
\]

and

\[
q\le\frac2N.
\]

### Solution
Define the random variable


$$
X=\sum_{i=1}^N\mathbf 1_{A_i},
$$


the number of events that occur.

We are told


$$
1\le X\le2
$$


almost surely.

### Proving $p\ge1/N$

Taking expectations,


$$
E[X]
=
\sum_{i=1}^NP(A_i)
=
Np.
$$


Since $X\ge1$,


$$
E[X]\ge1.
$$


Therefore


$$
Np\ge1
$$


and hence


$$
\boxed{p\ge\frac1N}.
$$


### Proving $q\le2/N$

Because $X\le2$,


$$
\binom X2\le1.
$$


Taking expectations,


$$
E\left[\binom X2\right]\le1.
$$


But


$$
\binom X2
=
\sum_{1\le i<j\le N}
\mathbf 1_{A_i\cap A_j}.
$$


Therefore


$$
E\left[\binom X2\right]
=
\sum_{i<j}P(A_i\cap A_j)
=
\binom N2q.
$$


Thus


$$
\binom N2q\le1.
$$


So actually the stronger bound


$$
q\le\frac{2}{N(N-1)}
$$


holds.

Since


$$
\frac{2}{N(N-1)}\le\frac2N
$$


for $N\ge2$,


$$
\boxed{q\le\frac2N}.
$$


---


---

# 22. Question

Three friends are hanging out. To keep things simple, assume their birthdays are uniformly and independently distributed across the 365-day year. What’s the probability that some (i.e. either two or three) of the people in this group have a birthday in common?

### Solution
It is easier to calculate the complement.

Let $D$ be the event that all three birthdays are different.

The first person's birthday can be anything:


$$
P(\text{first})=1.
$$


The second must avoid the first person's birthday:


$$
P(\text{second different})=\frac{364}{365}.
$$


The third must avoid the first two:


$$
P(\text{third different})=\frac{363}{365}.
$$


Thus


$$
P(D)
=
\frac{364}{365}\frac{363}{365}.
$$


Therefore


$$
P(\text{at least one match})
=
1-\frac{364\cdot363}{365^2}.
$$


So


$$
\boxed{
P(\text{some birthday is shared})
=
1-\frac{364\cdot363}{365^2}
\approx0.008204
}.
$$


Thus the probability is about $0.82\%$.


---


---

# 23. Question

You invite some friends to a hat-themed party. As the night progresses, you decide to play a game: everyone will line up and place their hat on the ground in front of them. The guests will then be reordered randomly, with all orderings equally likely. Afterward, each guest will grab the hat in front of them.

We’re interested in the probability that at least one guest is wearing their own hat at the end of the game. What does that probability converge to as the number of guests grows infinitely large?

Let \(A_i\) be the event that \(i\)-th person picks own hat. For example \(A_5\) represents that 5-th person picks own hat.

We are interested in probability that at least one guest is wearing their own hat which is

\[
P\left(\bigcup_{i=1}^N A_i\right).
\]

### Solution
This is the complement of the derangement problem.

The event


$$
\bigcap_{i=1}^N A_i^c
$$


means nobody gets their own hat.

From Question 20,


$$
P(\text{nobody gets own hat})
=
\sum_{k=0}^N\frac{(-1)^k}{k!}.
$$


Therefore


$$
P\left(\bigcup_{i=1}^N A_i\right)
=
1-\sum_{k=0}^N\frac{(-1)^k}{k!}.
$$


Hence


$$
\boxed{
P(\text{at least one correct hat})
=
1-\sum_{k=0}^N\frac{(-1)^k}{k!}
}.
$$


Taking the limit,


$$
\lim_{N\to\infty}
P(\text{at least one correct hat})
=
1-\frac1e.
$$


Therefore


$$
\boxed{
\lim_{N\to\infty}P\left(\bigcup_{i=1}^N A_i\right)
=
1-\frac1e
\approx0.6321
}.
$$


---


---

# 24. Question

Let \(A,B\) be events such that

\[
P(A)=\frac14
\]

and

\[
P(B)=\frac12.
\]

Find maximum possible values for \(P(A\cup B)\) and \(P(A\cap B)\).

### Solution
### 1. Maximum of $P(A\cup B)$

The addition rule gives


$$
P(A\cup B)
=
P(A)+P(B)-P(A\cap B).
$$


To maximize the union, minimize the intersection.

The smallest possible intersection is


$$
\max\{0,P(A)+P(B)-1\}.
$$


Here,


$$
\frac14+\frac12-1=-\frac14,
$$


so the minimum intersection is 0.

Thus


$$
P(A\cup B)_{\max}
=
\frac14+\frac12
=
\boxed{\frac34}.
$$


### 2. Maximum of $P(A\cap B)$

An intersection cannot be larger than either event:


$$
P(A\cap B)\le\min(P(A),P(B)).
$$


Therefore


$$
P(A\cap B)\le\frac14.
$$


This value is achievable by taking


$$
A\subseteq B.
$$


Hence


$$
\boxed{P(A\cap B)_{\max}=\frac14}.
$$


---


---

# 25. Question

Assume a certain city X experiences a hot day with probability 0.4 and a cold day with probability 0.6. Each hot day experiences rain with probability 0.2 while a cold day experiences rain with probability 0.7. Given a particular day is rainy, what is the probability that the day is hot?

### Solution
Use Bayes' theorem:


$$
P(H\mid R)
=
\frac{P(R\mid H)P(H)}
{P(R)}.
$$


By total probability,


$$
P(R)
=
P(R\mid H)P(H)
+
P(R\mid C)P(C).
$$


Therefore


$$
P(R)
=
0.2(0.4)+0.7(0.6)
=
0.08+0.42
=
0.50.
$$


Hence


$$
P(H\mid R)
=
\frac{0.2(0.4)}{0.5}
=
\boxed{0.16}.
$$


So the probability the rainy day is hot is $16\%$.


---


---

# 26. Question

Let \(A_i\) be a sequence of events such that

\[
P(A_i)=\frac1{2^i}\quad\forall i\in\mathbb N.
\]

The \(A_i\)'s partition the sample space. Let \(C\) be another event such that

\[
P(C\mid A_i)=\frac13\quad\forall i\in\mathbb N.
\]

Find \(P(C)\).

### Solution
Because $\{A_i\}$ is a partition, the law of total probability gives


$$
P(C)
=
\sum_{i=1}^{\infty}
P(C\mid A_i)P(A_i).
$$


Substitute:


$$
P(C)
=
\sum_{i=1}^{\infty}
\frac13\frac1{2^i}.
$$


Thus


$$
P(C)
=
\frac13
\sum_{i=1}^{\infty}\left(\frac12\right)^i.
$$


The geometric series is


$$
\sum_{i=1}^{\infty}\left(\frac12\right)^i=1.
$$


Therefore


$$
\boxed{P(C)=\frac13}.
$$


---


---

# 27. Question

Let \(A\) and \(B\) be events such that

\[
P(A\mid B)>P(A).
\]

Show that

\[
P(B\mid A)>P(B)
\]

and

\[
P(A\mid B^c)<P(A).
\]

### Solution
Start with


$$
P(A\mid B)>P(A).
$$


Multiply by $P(B)$:


$$
P(A\cap B)>P(A)P(B).
$$


Now divide by $P(A)$:


$$
\frac{P(A\cap B)}{P(A)}>P(B).
$$


But


$$
\frac{P(A\cap B)}{P(A)}=P(B\mid A).
$$


Therefore


$$
\boxed{P(B\mid A)>P(B)}.
$$


For the second result, use total probability:


$$
P(A)
=
P(A\mid B)P(B)
+
P(A\mid B^c)P(B^c).
$$


We are given


$$
P(A\mid B)>P(A).
$$


If $P(A\mid B^c)\ge P(A)$, then the weighted average of $P(A\mid B)$ and $P(A\mid B^c)$ would be greater than $P(A)$, contradicting the equality above.

Therefore


$$
\boxed{P(A\mid B^c)<P(A)}.
$$


---


---

# 28. Question

A positive integer is selected, with

\[
P(I=n)=\frac1{2^n},\qquad n=1,2,\ldots.
\]

If \(I\) takes the value \(n\), a coin with probability of heads equal to \(e^{-n}\) is tossed once. Find the probability that the resulting toss will be a head.

### Solution
Use the law of total probability:


$$
P(H)
=
\sum_{n=1}^{\infty}
P(H\mid I=n)P(I=n).
$$


Therefore


$$
P(H)
=
\sum_{n=1}^{\infty}
e^{-n}\frac1{2^n}.
$$


Rewrite:


$$
P(H)
=
\sum_{n=1}^{\infty}
\left(\frac1{2e}\right)^n.
$$


This is a geometric series with first term


$$
\frac1{2e}
$$


and common ratio


$$
\frac1{2e}.
$$


Hence


$$
P(H)
=
\frac{\frac1{2e}}{1-\frac1{2e}}
=
\boxed{\frac1{2e-1}}.
$$


---


---

# 29. Question

Given a sequence of events \(A_1,A_2,\ldots,A_n\) satisfying

\[
\sum_{i=1}^nP(A_i)
=
P\left(\bigcup_{i=1}^nA_i\right).
\]

Prove that

\[
P(A_i\cap A_j)=0
\]

for all \(i,j\), \(i\ne j\).

### Solution
Define


$$
X=\sum_{i=1}^n\mathbf1_{A_i}.
$$


Then


$$
E[X]
=
\sum_{i=1}^nP(A_i).
$$


But the union event occurs exactly when $X\ge1$. Therefore


$$
P\left(\bigcup_iA_i\right)=P(X\ge1).
$$


The assumption gives


$$
E[X]=P(X\ge1).
$$


Now note that


$$
X\ge\mathbf1_{\{X\ge1\}},
$$


with strict inequality whenever $X\ge2$.

Since their expectations are equal,


$$
P(X\ge2)=0.
$$


Therefore, with probability 1, at most one of the events $A_i$ occurs.

Hence for every $i\ne j$,


$$
\boxed{P(A_i\cap A_j)=0}.
$$


Thus the events are **pairwise disjoint almost surely**.


---


---

# 30. Question

A man is known to speak the truth 3 out of 4 times. He throws a die and reports that it is a six. Find the probability that it is actually a six.

### Solution
Let

- $S$: the die actually shows 6.
- $R$: the man reports 6.

Assume the standard interpretation of the problem:


$$
P(S)=\frac16
$$


and


$$
P(R\mid S)=\frac34.
$$


If the die is not a six, reporting "six" is a false statement, so under the usual binary truth/lie model,


$$
P(R\mid S^c)=\frac14.
$$


By Bayes' theorem,


$$
P(S\mid R)
=
\frac{P(R\mid S)P(S)}
{P(R\mid S)P(S)+P(R\mid S^c)P(S^c)}.
$$


Substitute:


$$
P(S\mid R)
=
\frac{\frac34\cdot\frac16}
{\frac34\cdot\frac16+\frac14\cdot\frac56}.
$$


The numerator is


$$
\frac18.
$$


The denominator is


$$
\frac18+\frac5{24}
=
\frac3{24}+\frac5{24}
=
\frac8{24}
=
\frac13.
$$


Therefore


$$
P(S\mid R)
=
\frac{1/8}{1/3}
=
\boxed{\frac38}.
$$


### Important assumption

Strictly speaking, "speaks the truth 3 out of 4 times" only tells us the probability that his statement is true. It does **not**, by itself, specify which false number he reports.

The answer


$$
\boxed{\frac38}
$$


uses the standard textbook assumption


$$
P(\text{reports 6}\mid\text{actual result is not 6})=\frac14.
$$


Without such an assumption about how he chooses a false report, the problem is under-specified.


---

# Final Answer Summary

| # | Answer |
|---|---|
| 1(a) | Example: die, $P(A\cap B)=1/3>P(A)P(B)=1/4$ |
| 1(b) | Example: die, $P(A\cap B)=1/6<P(A)P(B)=1/3$ |
| 2(a) | $3/8$ |
| 2(b) | $2/7$ |
| 2(c) | $9/14$ |
| 3(a) | Not independent |
| 3(b) | Independent |
| 3(c) | Independent |
| 4 | $A^c,B^c$ are independent |
| 5 | Sample space = complete tournament outcomes/brackets |
| 6 | $\displaystyle\sum_{j=0}^k(-1)^j\binom{k}{j}((k-j)/k)^N$ |
| 7 | $1/120$ |
| 8 | $25/72$ |
| 9 | $P(B_2)=1/2,\;P(B_2\mid B_1)=2/3$ |
| 10 | $388889/10^6\approx0.388889$ |
| 11 | $P(K=k)=1/(N+1)$ |
| 12 | $\displaystyle \binom{k+2}{k}/2^{k+3},\ k=0,1,2$ |
| 13(a) | Not independent |
| 13(b) | Independent |
| 14 | A: $10/33$, B: $14/33$, C: $9/33$ |
| 15(a) | $P(A\cap B)\ge P(A)+P(B)-1$ |
| 15(b) | $P(\cap_iA_i)\ge\sum_iP(A_i)-(n-1)$ |
| 16 | $P(A\cap B)>1-2\delta$ |
| 17 | $P(B_n)\le n(1-p)^{n-1}$, limit $0$ |
| 18(a) | $1-(1-p_i)^k$ |
| 18(b) | $1-(1-p_i-p_j)^k$ |
| 18(c) | Intersection formula divided by $P(A_j)$ |
| 19 | $P(E_1)=1/3,\;P(E_2\mid C)=2/3$ |
| 20 | $P_n=\sum_{k=0}^n(-1)^k/k!\to1/e$ |
| 21 | $p\ge1/N,\;q\le2/N$ |
| 22 | $\displaystyle1-\frac{364\cdot363}{365^2}\approx0.008204$ |
| 23 | $\displaystyle1-\sum_{k=0}^N(-1)^k/k!\to1-1/e$ |
| 24 | $\max P(A\cup B)=3/4,\;\max P(A\cap B)=1/4$ |
| 25 | $0.16$ |
| 26 | $1/3$ |
| 27 | $P(B\mid A)>P(B)$, $P(A\mid B^c)<P(A)$ |
| 28 | $1/(2e-1)$ |
| 29 | $P(A_i\cap A_j)=0$ |
| 30 | $3/8$, under the standard reporting assumption |

---

## Problem-Solving Patterns to Remember

### 1. Independence

Always test


$$
\boxed{P(A\cap B)=P(A)P(B)}
$$


Do not conclude independence merely because the events look unrelated.

### 2. Conditional probability

Start with


$$
\boxed{P(A\mid B)=\frac{P(A\cap B)}{P(B)}}.
$$


### 3. Bayes' theorem

When the question says **"given that we observed..."** and asks you to infer the underlying cause, think Bayes:


$$
\boxed{
P(A\mid B)
=
\frac{P(B\mid A)P(A)}
{\sum_iP(B\mid A_i)P(A_i)}
}.
$$


### 4. "At least one"

Usually use the complement:


$$
\boxed{
P(\text{at least one})
=
1-P(\text{none})
}.
$$


### 5. Inclusion-exclusion

For several overlapping events:


$$
\boxed{
P\left(\bigcup_iA_i\right)
}
$$


is often easiest using inclusion-exclusion.

### 6. Symmetry

Questions involving:

- random positions,
- random people,
- random hats,
- random birthdays,
- random tournament choices,

often become much simpler when you identify symmetric outcomes.

### 7. Counting random sequences

If every sequence has probability $p$, use


$$
P(\text{event})
=
\text{number of favorable sequences}\times p.
$$


### 8. Complements are powerful

For difficult intersections/unions, ask:

> "Would the complement be easier to describe?"

This is especially useful for:

- at least one,
- nobody,
- all distinct,
- all instructors teach,
- no isolated nodes,
- no one gets their own hat.
