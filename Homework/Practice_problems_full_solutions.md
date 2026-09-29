---
title: Probability — Joint Distributions, Expectation and Variance
tags:
  - probability
  - joint-distributions
  - conditional-probability
  - expectation
  - obsidian
---

# Probability — Questions and Solutions (Set 3)

> [!note] How to use this file
> Each **complete question**, including every subpart, appears before its **complete solution**. Equations use Obsidian's `$...$` and `$$...$$` notation. Assumptions needed to resolve ambiguous wording are identified explicitly.

---

# 1. Joint continuous distribution

## Question

There are two jointly continuous random variables $X$ and $Y$ with joint PDF

$$
f_{X,Y}(x,y)=\begin{cases}
\dfrac{x^2}{4}+\dfrac{y^2}{4}+\dfrac{xy}{6},&0\le x\le1,\ 0\le y\le2,\\
0,&\text{otherwise}.
\end{cases}
$$

For $0\le y\le2$, find:

**(a)** The conditional PDF of $X$ given $Y=y$.

**(b)** $P(X<\tfrac12\mid Y=y)$.

## Solution

First integrate the joint density over $x$ to obtain the marginal of $Y$:

$$
\begin{aligned}
f_Y(y)&=\int_0^1\left(\frac{x^2}{4}+\frac{y^2}{4}+\frac{xy}{6}\right)dx\\
&=\frac1{12}+\frac{y^2}{4}+\frac y{12}\\
&=\frac{1+y+3y^2}{12},\quad 0\le y\le2.
\end{aligned}
$$

### (a) Conditional PDF

By definition, $f_{X\mid Y}(x\mid y)=f_{X,Y}(x,y)/f_Y(y)$. Thus

$$
\boxed{f_{X\mid Y}(x\mid y)=\begin{cases}
\dfrac{3x^2+3y^2+2xy}{1+y+3y^2},&0\le x\le1,\\
0,&\text{otherwise},
\end{cases}}
$$

for $0\le y\le2$. The denominator is positive throughout this range.

### (b) Conditional probability

$$
\begin{aligned}
P(X<\tfrac12\mid Y=y)
&=\int_0^{1/2}f_{X\mid Y}(x\mid y)\,dx\\
&=\frac{\frac18+\frac32y^2+\frac14y}{1+y+3y^2}.
\end{aligned}
$$

Therefore

$$
\boxed{P(X<\tfrac12\mid Y=y)=\frac{1+2y+12y^2}{8(1+y+3y^2)}}.
$$

---

# 2. Joint CDF from a joint PMF

## Question

Two discrete random variables $X$ and $Y$ have the joint distribution below. Find the following, where $F_{X,Y}(x,y)$ denotes the joint CDF.

| $Y\backslash X$ | $1$ | $2$ | $3$ |
|---|---:|---:|---:|
| $1$ | $3/12$ | $1/12$ | $3/12$ |
| $2$ | $1/12$ | $3/12$ | $1/12$ |

**(a)** $F_{X,Y}(1,1)$

**(b)** $F_{X,Y}(1.5,4)$

**(c)** $F_{X,Y}(4,9)$

**(d)** $F_{X,Y}(1,-1.5)$

## Solution

The joint CDF is

$$
F_{X,Y}(x,y)=P(X\le x,Y\le y).
$$

Sum only table cells satisfying **both** inequalities.

### (a)

Only $(X,Y)=(1,1)$ qualifies:

$$\boxed{F_{X,Y}(1,1)=\frac3{12}=\frac14}.$$

### (b)

$X\le1.5$ means $X=1$; $Y\le4$ includes both rows:

$$\boxed{F_{X,Y}(1.5,4)=\frac3{12}+\frac1{12}=\frac13}.$$

### (c)

All six possible outcomes qualify:

$$\boxed{F_{X,Y}(4,9)=1}.$$

### (d)

No possible $Y$ is at most $-1.5$:

$$\boxed{F_{X,Y}(1,-1.5)=0}.$$

---

# 3. Conditional density involving an exponential

## Question

The random variables $X,Y$ have joint PDF

$$
f_{X,Y}(x,y)=\begin{cases}
cx(y-x)e^{-y},&0\le x\le y,\\
0,&\text{elsewhere},
\end{cases}
$$

where $c$ is a constant.

**(a)** Compute $c$.

**(b)** Obtain $f_{X\mid Y}(x\mid y)$.

## Solution

### (a) Normalizing constant

A joint PDF integrates to one:

$$
1=c\int_0^\infty e^{-y}\left[\int_0^y x(y-x)\,dx\right]dy.
$$

The inner integral is

$$
\int_0^y x(y-x)dx=\left[\frac{yx^2}{2}-\frac{x^3}{3}\right]_0^y=\frac{y^3}{6}.
$$

Since $\int_0^\infty y^3e^{-y}dy=3!=6$,

$$1=\frac c6\cdot6=c\quad\Longrightarrow\quad\boxed{c=1}.$$

### (b) Conditional density

For $y>0$,

$$
f_Y(y)=\int_0^y x(y-x)e^{-y}dx=\frac{y^3e^{-y}}6.
$$

Divide the joint PDF by this marginal:

$$
\boxed{f_{X\mid Y}(x\mid y)=\begin{cases}
\dfrac{6x(y-x)}{y^3},&0\le x\le y,\\
0,&\text{otherwise},
\end{cases}\quad y>0.}
$$

At $y=0$, $f_Y(0)=0$, so the conditional density is only specified where $f_Y(y)>0$.

---

# 4. Comparing independent exponential lifetimes

## Question

Consider two independent random variables $X_1\sim\operatorname{Exp}(\lambda_1)$ and $X_2\sim\operatorname{Exp}(\lambda_2)$. Find $P(X_1\le X_2)$.

Recall that $X\sim\operatorname{Exp}(\lambda)$ has PDF $f_X(x)=\lambda e^{-\lambda x}$ for $x\ge0$.

## Solution

Condition on $X_1=x$. The event $X_2\ge x$ has probability $e^{-\lambda_2x}$, so

$$
\begin{aligned}
P(X_1\le X_2)
&=\int_0^\infty P(X_2\ge x)f_{X_1}(x)dx\\
&=\int_0^\infty e^{-\lambda_2x}\lambda_1e^{-\lambda_1x}dx\\
&=\lambda_1\int_0^\infty e^{-(\lambda_1+\lambda_2)x}dx.
\end{aligned}
$$

Hence

$$\boxed{P(X_1\le X_2)=\frac{\lambda_1}{\lambda_1+\lambda_2}}.$$

The probability of an exact tie is zero because the variables are continuous.

---

# 5. Geometric distribution conditioned on an even value

## Question

Let $N$ be geometric with PMF

$$p_N(k)=p(1-p)^{k-1},\quad k=1,2,\ldots,\quad p\in(0,1).$$

Find the conditional PMF $p_N(k\mid A)=P(N=k\mid N\in A)$ if $A=\{N\text{ is even}\}$.

## Solution

Write $q=1-p$. First compute the conditioning probability:

$$
\begin{aligned}
P(A)&=\sum_{j=1}^\infty P(N=2j)\\
&=\sum_{j=1}^\infty pq^{2j-1}
=\frac{pq}{1-q^2}
=\frac q{1+q}
=\frac{1-p}{2-p}.
\end{aligned}
$$

For even $k\ge2$,

$$
P(N=k\mid A)=\frac{pq^{k-1}}{q/(1+q)}=p(1+q)q^{k-2}.
$$

Thus

$$
\boxed{p_N(k\mid A)=\begin{cases}
p(2-p)(1-p)^{k-2},&k=2,4,6,\ldots,\\
0,&\text{otherwise}.
\end{cases}}
$$

Check: summing over $k=2j$ yields $p(2-p)/(1-(1-p)^2)=1$.

---

# 6. First failure and complete darkness: CDFs

## Question

Suppose $n$ tube lights in a room are turned on at time $0$. Their lifetimes are independent and exponentially distributed with parameter $\mu$.

**(a)** What is the CDF of the time after which the first tube light fuses out?

**(b)** Find the CDF of the time after which the room goes dark.

## Solution

Let $T_i\sim\operatorname{Exp}(\mu)$ independently, with $n\ge1$.

### (a) First light to fail

The first failure time is $T_{\min}=\min(T_1,\ldots,T_n)$. For $t\ge0$,

$$
\begin{aligned}
P(T_{\min}>t)&=P(T_1>t,\ldots,T_n>t)\\
&=\prod_{i=1}^n e^{-\mu t}=e^{-n\mu t}.
\end{aligned}
$$

Therefore

$$
\boxed{F_{T_{\min}}(t)=\begin{cases}0,&t<0,\\1-e^{-n\mu t},&t\ge0.\end{cases}}
$$

### (b) All lights have failed

The room goes dark at $T_{\max}=\max(T_1,\ldots,T_n)$. For $t\ge0$,

$$
\begin{aligned}
P(T_{\max}\le t)&=P(T_1\le t,\ldots,T_n\le t)\\
&=\prod_{i=1}^n(1-e^{-\mu t})=(1-e^{-\mu t})^n.
\end{aligned}
$$

Therefore

$$
\boxed{F_{T_{\max}}(t)=\begin{cases}0,&t<0,\\(1-e^{-\mu t})^n,&t\ge0.\end{cases}}
$$

---

# 7. Document length conditional on printer choice

## Question

The number of pages $X$ in a document has PMF

$$
P_X(x)=\begin{cases}
0.15,&x=1,2,3,4,\\
0.10,&x=5,6,7,8,\\
0,&\text{otherwise}.
\end{cases}
$$

A firm sends all documents with an even number of pages to printer A and all documents with an odd number of pages to printer B.

**(a)** Find the conditional PMF of $X$ given that the document was sent to printer A.

**(b)** Find the conditional PMF of $X$ given that the document was sent to printer B **and** had no more than six pages.

## Solution

### (a) Printer A

Printer A receives $X\in\{2,4,6,8\}$, with total probability

$$P(A)=0.15+0.15+0.10+0.10=0.50.$$

Divide each qualifying probability by $0.5$:

$$
\boxed{P(X=x\mid A)=\begin{cases}
0.30,&x=2,4,\\
0.20,&x=6,8,\\
0,&\text{otherwise}.
\end{cases}}
$$

### (b) Printer B and at most six pages

The conditioning event is $B\cap\{X\le6\}=\{X=1,3,5\}$. Its probability is

$$0.15+0.15+0.10=0.40.$$

Therefore

$$
\boxed{P(X=x\mid B,X\le6)=\begin{cases}
\dfrac38,&x=1,3,\\
\dfrac14,&x=5,\\
0,&\text{otherwise}.
\end{cases}}
$$

The probabilities sum to $3/8+3/8+1/4=1$.

---

# 8. Randomly selected coin

## Question

A positive integer is selected with $P(I=n)=1/2^n$, $n=1,2,\ldots$. If $I=n$, a coin with probability of heads $e^{-n}$ is tossed once. Find the probability of heads.

## Solution

Condition on the selected integer and apply the law of total probability:

$$
\begin{aligned}
P(H)&=\sum_{n=1}^\infty P(H\mid I=n)P(I=n)\\
&=\sum_{n=1}^\infty e^{-n}2^{-n}\\
&=\sum_{n=1}^\infty\left(\frac1{2e}\right)^n.
\end{aligned}
$$

The geometric-series formula gives

$$\boxed{P(H)=\frac{1/(2e)}{1-1/(2e)}=\frac1{2e-1}}.$$

---

# 9. Joint PDF on a curved region

## Question

Let $f(x,y)=cx^2y$ for $x^2\le y\le1$ (and zero elsewhere) denote the joint PDF of $(X,Y)$. Find:

**(a)** $c$

**(b)** $P(|X|\ge Y)$

**(c)** The marginals $f_X(x)$ and $f_Y(y)$.

## Solution

The support is $-1\le x\le1$ and $x^2\le y\le1$. Equivalently, $0\le y\le1$ and $-\sqrt y\le x\le\sqrt y$.

### (a) Normalizing constant

$$
\begin{aligned}
1&=c\int_{-1}^1\int_{x^2}^1x^2y\,dy\,dx\\
&=\frac c2\int_{-1}^1x^2(1-x^4)dx\\
&=c\left(\frac13-\frac17\right)=\frac{4c}{21}.
\end{aligned}
$$

Thus $\boxed{c=21/4}$.

### (b) $P(|X|\ge Y)$

Within the support, this event requires $x^2\le y\le|x|$. Integrate over both positive and negative $x$:

$$
\begin{aligned}
P(|X|\ge Y)
&=\frac{21}{4}\int_{-1}^1\int_{x^2}^{|x|}x^2y\,dy\,dx\\
&=\frac{21}{8}\int_{-1}^1x^2(x^2-x^4)dx\\
&=\frac{21}{4}\left(\frac15-\frac17\right)\\
&=\boxed{\frac3{10}}.
\end{aligned}
$$

### (c) Marginals

For $-1\le x\le1$,

$$
\begin{aligned}
f_X(x)&=\int_{x^2}^1\frac{21}{4}x^2y\,dy\\
&=\frac{21}{8}x^2(1-x^4).
\end{aligned}
$$

Thus

$$
\boxed{f_X(x)=\begin{cases}\dfrac{21}{8}x^2(1-x^4),&-1\le x\le1,\\0,&\text{otherwise}.\end{cases}}
$$

For $0\le y\le1$,

$$
\begin{aligned}
f_Y(y)&=\int_{-\sqrt y}^{\sqrt y}\frac{21}{4}x^2y\,dx\\
&=\frac{21}{4}y\cdot\frac{2y^{3/2}}3=\frac72y^{5/2}.
\end{aligned}
$$

Therefore

$$
\boxed{f_Y(y)=\begin{cases}\dfrac72y^{5/2},&0\le y\le1,\\0,&\text{otherwise}.\end{cases}}
$$

---

# 10. Geometric waiting time after previous failures

## Question

Let $X$ be the number of tosses of a biased coin required to obtain the first head. The first head has not occurred in the first $k$ tosses. What is the probability that you will have to toss the coin $n$ more times?

## Solution

Let $p=P(H)$, with independent tosses. The condition is $X>k$. If the question means **exactly $n$ additional tosses**, then

$$
\begin{aligned}
P(X=k+n\mid X>k)
&=\frac{P(X=k+n)}{P(X>k)}\\
&=\frac{(1-p)^{k+n-1}p}{(1-p)^k}\\
&=\boxed{(1-p)^{n-1}p},\quad n=1,2,\ldots.
\end{aligned}
$$

This is the memoryless property of the geometric distribution: previous tails do not change the future waiting-time distribution.

> [!note] Wording distinction
> If **at least $n$ additional tosses** are needed, the probability is $P(X\ge k+n\mid X>k)=(1-p)^{n-1}$. If the next $n$ additional tosses must **all be tails**, the probability is $(1-p)^n$.

---

# 11. Isolated nodes and edge counts in a random graph

## Question

Consider an undirected random graph $G$ with $n$ nodes. Each of the $\binom n2$ possible edges is independently included with probability $p$. Define

$$
I_i=\begin{cases}1,&\text{node }i\text{ is isolated (no incident edge)},\\0,&\text{otherwise}.\end{cases}
$$

**(a)** For $i\ne j$, are $I_i,I_j$ independent? Provide a mathematical argument.

**(b)** Find the expected number of isolated nodes in $G$.

**(c)** Let $E$ denote the number of edges in $G$. Find $\mathbb E[E]$.

## Solution

Write $q=1-p$.

### (a) Dependence of isolation indicators

A given node has $n-1$ possible incident edges, all of which must be absent for it to be isolated:

$$P(I_i=1)=q^{n-1}.$$

For **both** distinct nodes $i,j$ to be isolated, all edges incident to either must be absent. There are $2(n-1)-1=2n-3$ distinct such edges (the edge $ij$ was counted twice):

$$P(I_i=1,I_j=1)=q^{2n-3}.$$

If the indicators were independent, the joint probability would equal $q^{2n-2}$. For $n\ge2$ and $0<p<1$, these are unequal:

$$q^{2n-3}\ne q^{2n-2}.$$

Thus $\boxed{I_i,I_j\text{ are not independent for }0<p<1}$. At the degenerate endpoints $p=0$ or $p=1$, the indicators are constant and therefore independent.

### (b) Expected isolated nodes

Let $S=\sum_{i=1}^n I_i$. By linearity of expectation,

$$\boxed{\mathbb E[S]=\sum_{i=1}^n\mathbb E[I_i]=n(1-p)^{n-1}}.$$

Independence of the indicators is **not** required for linearity.

### (c) Expected edges

For each possible edge $e$, let $J_e$ indicate whether it exists. Then $E=\sum_eJ_e$ and $\mathbb E[J_e]=p$. Consequently,

$$\boxed{\mathbb E[E]=\binom n2p=\frac{n(n-1)}2p}.$$

---

# 12. Transformations of expectation and variance

## Question

If $\mathbb E[X]=1$ and $\operatorname{Var}(X)=5$, find:

**(a)** $\mathbb E[(2+X)^2]$

**(b)** $\operatorname{Var}(4+3X)$.

## Solution

First compute the second moment:

$$\mathbb E[X^2]=\operatorname{Var}(X)+(\mathbb E[X])^2=5+1=6.$$

### (a)

$$
\begin{aligned}
\mathbb E[(2+X)^2]
&=\mathbb E[X^2+4X+4]\\
&=6+4(1)+4=\boxed{14}.
\end{aligned}
$$

### (b)

Adding a constant does not change variance; multiplying by $3$ multiplies variance by $3^2$:

$$\boxed{\operatorname{Var}(4+3X)=9\operatorname{Var}(X)=45}.$$

---

# 13. Finding normal-distribution parameters from mixed moments

## Question

Three independent random variables $X,Y,Z$ follow $X\sim N(\mu,\sigma^2)$ and $Y,Z\sim\operatorname{Uniform}(0,2)$. Given

- $\mathbb E[X^2Y+XYZ]=13$
- $\mathbb E[XY^2+ZX^2]=14$

find the numerical values of $\mu,\sigma$.

## Solution

By independence and standard moments,

$$
\mathbb E[X]=\mu,\quad \mathbb E[X^2]=\mu^2+\sigma^2,\quad
\mathbb E[Y]=\mathbb E[Z]=1,\quad\mathbb E[Y^2]=\frac43.
$$

The first condition becomes

$$
\begin{aligned}
13&=\mathbb E[X^2]\mathbb E[Y]+\mathbb E[X]\mathbb E[Y]\mathbb E[Z]\\
&=\mu^2+\sigma^2+\mu.
\end{aligned}
$$

The second condition becomes

$$
\begin{aligned}
14&=\mathbb E[X]\mathbb E[Y^2]+\mathbb E[Z]\mathbb E[X^2]\\
&=\frac43\mu+\mu^2+\sigma^2.
\end{aligned}
$$

Subtracting the first equation from the second gives

$$1=\frac\mu3\quad\Longrightarrow\quad\boxed{\mu=3}.$$

Substitute into the first equation:

$$9+\sigma^2+3=13\quad\Longrightarrow\quad\sigma^2=1.$$

As a standard deviation is nonnegative,

$$\boxed{\mu=3,\qquad\sigma=1}.$$

---

# 14. Balls and bins: empty-bin expectation and variance

## Question

Consider $k$ balls and $n$ bins ($k\ge n$). Each ball is placed independently and uniformly at random into one of the $n$ bins. Let $B$ denote the number of empty bins.

**(a)** What is $\mathbb E[B]$?

**(b)** What is $\operatorname{Var}(B)$?

## Solution

Define $I_i=1$ if bin $i$ is empty and $0$ otherwise. Then $B=\sum_{i=1}^n I_i$.

Let

$$q=P(I_i=1)=\left(1-\frac1n\right)^k.$$

For distinct bins $i,j$, the probability that **both** are empty is

$$r=P(I_i=1,I_j=1)=\left(1-\frac2n\right)^k.$$

### (a) Expectation

By linearity,

$$\boxed{\mathbb E[B]=nq=n\left(1-\frac1n\right)^k}.$$

### (b) Variance

Use the variance-of-a-sum identity:

$$
\operatorname{Var}(B)=\sum_i\operatorname{Var}(I_i)+2\sum_{i<j}\operatorname{Cov}(I_i,I_j).
$$

Since $I_i$ is Bernoulli, $\operatorname{Var}(I_i)=q(1-q)$. Also,

$$\operatorname{Cov}(I_i,I_j)=r-q^2.$$

There are $\binom n2$ distinct pairs, so

$$
\boxed{\operatorname{Var}(B)=nq(1-q)+n(n-1)(r-q^2)}.
$$

Substituting the definitions,

$$
\boxed{\begin{aligned}
\operatorname{Var}(B)={}&n\left(1-\frac1n\right)^k\left[1-\left(1-\frac1n\right)^k\right]\\
&+n(n-1)\left[\left(1-\frac2n\right)^k-\left(1-\frac1n\right)^{2k}\right].
\end{aligned}}
$$

For $n=1$, the single bin is never empty when $k\ge1$, so $\mathbb E[B]=\operatorname{Var}(B)=0$; interpret the pair term as absent.

---

# 15. Covariance, independence, uncorrelatedness and orthogonality

## Question

Consider discrete random variables $X,Y$ with the following joint PMF:

| $X\backslash Y$ | $-1$ | $0$ | $1$ |
|---|---:|---:|---:|
| $0$ | $1/6$ | $1/6$ | $0$ |
| $1$ | $0$ | $0$ | $1/3$ |
| $3$ | $1/6$ | $1/6$ | $0$ |

**(a)** Find the covariance matrix for $(X,Y)$.

**(b)** Are $X,Y$ independent? Justify.

**(c)** Are $X,Y$ uncorrelated? Justify.

**(d)** Are $X,Y$ orthogonal? Justify.

## Solution

The marginal probabilities are $P(X=0)=P(X=1)=P(X=3)=1/3$ and $P(Y=-1)=P(Y=0)=P(Y=1)=1/3$.

Calculate moments:

$$
\mathbb E[X]=\frac{0+1+3}{3}=\frac43,\qquad
\mathbb E[X^2]=\frac{0+1+9}{3}=\frac{10}{3}.
$$

$$
\operatorname{Var}(X)=\frac{10}{3}-\left(\frac43\right)^2=\frac{14}{9}.
$$

$$
\mathbb E[Y]=\frac{-1+0+1}{3}=0,\qquad
\mathbb E[Y^2]=\frac{1+0+1}{3}=\frac23.
$$

$$\operatorname{Var}(Y)=\frac23.$$

Only two nonzero-PMF cells contribute to $XY$: $(1,1)$ and $(3,-1)$. Thus

$$
\mathbb E[XY]=1\cdot1\cdot\frac13+3\cdot(-1)\cdot\frac16=\frac13-\frac12=-\frac16.
$$

Therefore

$$\operatorname{Cov}(X,Y)=\mathbb E[XY]-\mathbb E[X]\mathbb E[Y]=-\frac16.$$

### (a) Covariance matrix

$$
\boxed{\Sigma=\begin{pmatrix}
\frac{14}{9}&-\frac16\\[4pt]
-\frac16&\frac23
\end{pmatrix}}.
$$

### (b) Independence

No. For example, $P(X=1,Y=-1)=0$, whereas

$$P(X=1)P(Y=-1)=\frac13\cdot\frac13=\frac19.$$

These differ, so $\boxed{X,Y\text{ are not independent}}$.

### (c) Uncorrelatedness

No: $\operatorname{Cov}(X,Y)=-1/6\ne0$. Hence $\boxed{X,Y\text{ are correlated}}$.

### (d) Orthogonality

Random variables are orthogonal (in the usual $L^2$ sense) if $\mathbb E[XY]=0$. Here $\mathbb E[XY]=-1/6$, so $\boxed{X,Y\text{ are not orthogonal}}$.

---

# 16. Exponential light-bulb lifetimes: expected times

## Question

Suppose $n$ light bulbs in a room are turned on at time $0$. Their lifetimes are independent and exponentially distributed with parameter $\mu$.

**(a)** What is the expected time after which the first bulb fuses out?

**(b)** What is the expected time after which the room goes dark?

## Solution

Let $T_1,\ldots,T_n$ be the lifetimes.

### (a) First failure

The minimum of $n$ independent $\operatorname{Exp}(\mu)$ variables is $\operatorname{Exp}(n\mu)$ (see Question 6). Therefore

$$\boxed{\mathbb E[\min_iT_i]=\frac1{n\mu}}.$$

### (b) Last failure

The room goes dark when the **last** bulb fails, i.e., at $M=\max_iT_i$. From Question 6,

$$F_M(t)=(1-e^{-\mu t})^n,\qquad t\ge0.$$

For a nonnegative random variable, $\mathbb E[M]=\int_0^\infty P(M>t)dt$. Thus

$$
\begin{aligned}
\mathbb E[M]
&=\int_0^\infty\left[1-(1-e^{-\mu t})^n\right]dt\\
&=\frac1\mu\sum_{j=1}^n\frac1j.
\end{aligned}
$$

The last equality follows by expanding the binomial and integrating, or from the spacings of exponential order statistics. Hence

$$\boxed{\mathbb E[M]=\frac{H_n}{\mu}=\frac1\mu\left(1+\frac12+\cdots+\frac1n\right)}.$$

---

# 17. Variance of a mixed Bernoulli–normal expression

## Question

Let $X\sim\operatorname{Bernoulli}(p)$, $Y\sim N(0,1)$, and assume $X,Y$ are independent. Find

$$\operatorname{Var}((3X-1)Y).$$

## Solution

Let $W=(3X-1)Y$. Because $X,Y$ are independent and $\mathbb E[Y]=0$,

$$\mathbb E[W]=\mathbb E[3X-1]\mathbb E[Y]=0.$$

Therefore $\operatorname{Var}(W)=\mathbb E[W^2]$. By independence and $\mathbb E[Y^2]=1$,

$$
\begin{aligned}
\operatorname{Var}(W)
&=\mathbb E[(3X-1)^2]\mathbb E[Y^2]\\
&=\mathbb E[9X^2-6X+1].
\end{aligned}
$$

Since a Bernoulli variable satisfies $X^2=X$,

$$\boxed{\operatorname{Var}((3X-1)Y)=9p-6p+1=1+3p}.$$

Alternatively, $(3X-1)^2$ is $4$ with probability $p$ and $1$ with probability $1-p$, giving $4p+(1-p)=1+3p$.

---

# 18. Correlation in simple linear regression

## Question

In a simple linear regression, a feature $X$ is uniformly distributed on $[0,1]$. The target is generated by

$$Y=2X+\epsilon,$$

where $\epsilon\sim N(0,1)$ is independent noise. Find the correlation coefficient between $X$ and $Y$.

## Solution

For $X\sim\operatorname{Uniform}(0,1)$,

$$\operatorname{Var}(X)=\frac1{12}.$$

Independence gives $\operatorname{Cov}(X,\epsilon)=0$. Therefore

$$
\operatorname{Cov}(X,Y)=\operatorname{Cov}(X,2X+\epsilon)=2\operatorname{Var}(X)=\frac16.
$$

Also,

$$
\operatorname{Var}(Y)=4\operatorname{Var}(X)+\operatorname{Var}(\epsilon)=\frac13+1=\frac43.
$$

The Pearson correlation is

$$
\begin{aligned}
\rho_{X,Y}&=\frac{\operatorname{Cov}(X,Y)}{\sqrt{\operatorname{Var}(X)\operatorname{Var}(Y)}}\\
&=\frac{1/6}{\sqrt{(1/12)(4/3)}}\\
&=\boxed{\frac12}.
\end{aligned}
$$

---

# 19. Dataset coverage under sampling with replacement

## Question

A dataset $D$ contains $n$ distinct data points. A data scientist independently samples $k$ points **with replacement**, choosing uniformly from the dataset each time. Let $U$ be the number of data points never sampled.

**(a)** Find $\mathbb E[U]$.

**(b)** Define $\hat p=U/n$ as an estimator for the fraction of data points not seen in the sample. Compute $\mathbb E[\hat p]$.

**(c)** Is $\hat p$ an unbiased estimator for the probability that a given data point is not sampled?

## Solution

For each original data point $i$, define $I_i=1$ if it is never sampled and $0$ otherwise. Then $U=\sum_{i=1}^nI_i$.

For a particular point, the probability of avoiding it on one draw is $1-1/n$. Independence across the $k$ draws gives

$$q=P(I_i=1)=\left(1-\frac1n\right)^k.$$

### (a) Expected number never sampled

By linearity of expectation,

$$\boxed{\mathbb E[U]=\sum_{i=1}^n\mathbb E[I_i]=n\left(1-\frac1n\right)^k}.$$

### (b) Expected unseen fraction

Since $\hat p=U/n$,

$$\boxed{\mathbb E[\hat p]=\frac1n\mathbb E[U]=\left(1-\frac1n\right)^k}.$$

### (c) Unbiasedness

The target probability for any specified original point is $q=(1-1/n)^k$. Since $\mathbb E[\hat p]=q$,

$$\boxed{\hat p\text{ is unbiased for the probability a specified point is never sampled}.}$$

The indicators $I_i$ are generally **dependent**, but independence between them is not needed for the expectation calculation.
