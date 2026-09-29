---
title: Probability — Random Variables, CDFs and PMFs
tags:
  - probability
  - random-variables
  - pmf
  - cdf
  - pdf
  - obsidian
---

# Probability — Questions and Solutions

> [!note]
> **Obsidian math:** Inline equations use `$...$`; display equations use `$$...$$`.
>
> Each problem contains the **full question first**, followed immediately by its solution.


---

# 1. Question

Let \(X\) be a discrete random variable with the following PMF:

$$
P_X(x)=
\begin{cases}
0.1, & x=1,2,10,\\
0.3, & x=5,\\
0.4, & x=8,\\
0, & \text{otherwise}.
\end{cases}
$$

Find and plot the CDF of \(X\).

### Solution

The possible values of \(X\) are

$$
1,5,8,10.
$$

The PMF is

$$
P(X=1)=0.1,\quad
P(X=5)=0.3,\quad
P(X=8)=0.4,\quad
P(X=10)=0.1.
$$

The CDF is defined by

$$
F_X(x)=P(X\le x).
$$

We accumulate the PMF probabilities as \(x\) increases.

For \(x<1\),

$$
F_X(x)=0.
$$

For \(1\le x<5\),

$$
F_X(x)=0.1.
$$

For \(5\le x<8\),

$$
F_X(x)=0.1+0.3=0.4.
$$

For \(8\le x<10\),

$$
F_X(x)=0.1+0.3+0.4=0.8.
$$

For \(x\ge10\),

$$
F_X(x)=1.
$$

Therefore,

$$
\boxed{
F_X(x)=
\begin{cases}
0, & x<1,\\
0.1, & 1\le x<5,\\
0.4, & 5\le x<8,\\
0.8, & 8\le x<10,\\
1, & x\ge10.
\end{cases}}
$$

### Plot

The CDF is a **right-continuous step function**. It jumps:

- by \(0.1\) at \(x=1\),
- by \(0.3\) at \(x=5\),
- by \(0.4\) at \(x=8\),
- by \(0.1\) at \(x=10\).

You can reproduce the plot in Python with:

```python
import matplotlib.pyplot as plt

x = [1, 5, 8, 10]
F = [0.1, 0.4, 0.8, 1.0]

plt.step(x, F, where="post")
plt.xlabel("x")
plt.ylabel("F_X(x)")
plt.title("CDF of X")
plt.grid()
plt.show()
```




---

# 2. Question

Buses arrive at a bus-stop at 10-minute intervals starting at noon. A man arrives at the bus-stop at a random time \(X\) minutes after noon, where \(X\) has the CDF

$$
F_X(x)=
\begin{cases}
0, & x<0,\\
\dfrac{x}{60}, & 0\le x\le60,\\
1, & x>60.
\end{cases}
$$

What is the probability that the man waits less than 5 minutes for a bus?

### Solution

The buses arrive every 10 minutes:

$$
12{:}00,\ 12{:}10,\ 12{:}20,\ldots
$$

Since \(X\) is the man's arrival time after noon and

$$
0\le X\le60,
$$

the waiting time depends on \(X\).

A wait of less than 5 minutes occurs during the first 5 minutes after each bus:

$$
0<X<5,
$$

or

$$
10<X<15,
$$

or

$$
20<X<25,
$$

or

$$
30<X<35,
$$

or

$$
40<X<45,
$$

or

$$
50<X<55.
$$

Thus the favorable total length is

$$
6(5)=30\text{ minutes}.
$$

Since \(X\) is uniform on \([0,60]\),

$$
P(\text{wait}<5)=\frac{30}{60}.
$$

Therefore,

$$
\boxed{P(\text{wait}<5)=\frac12}.
$$

Equivalently, because the CDF is \(F_X(x)=x/60\), each 5-minute interval has probability \(5/60\), and there are six such intervals.




---

# 3. Question

I roll a fair die repeatedly until a number larger than 4 is observed. If \(N\) is the total number of times that I roll the die, find \(P(N=k)\), for \(k=1,2,3,\ldots\).

### Solution

A number larger than 4 means either 5 or 6.

Therefore the probability of success on any roll is

$$
p=P(5\text{ or }6)=\frac26=\frac13.
$$

The probability of failure is

$$
q=1-p=\frac23.
$$

For \(N=k\), the first \(k-1\) rolls must be failures and the \(k\)-th roll must be a success.

Therefore

$$
P(N=k)
=
\left(\frac23\right)^{k-1}\left(\frac13\right).
$$

Hence

$$
\boxed{
P(N=k)=\frac13\left(\frac23\right)^{k-1},
\qquad k=1,2,3,\ldots
}
$$

This is a geometric distribution with success probability \(1/3\).




---

# 4. Question

The random variable \(X\) has the following CDF:

$$
F_X(x)=
\begin{cases}
x, & 0\le x<\dfrac13,\\
\dfrac{3x+1}{6}, & \dfrac13\le x<\dfrac23,\\
x, & \dfrac23\le x<1,\\
1, & x\ge1.
\end{cases}
$$

**(a)** What is \(P(X<1/2)\)?

**(b)** What is \(P(X<2/3)\)?

**(c)** Is \(X\) a continuous random variable?

### Solution

The CDF is

$$
F_X(x)=P(X\le x).
$$

A key property is that for any \(a\),

$$
P(X<a)=F_X(a^-),
$$

where \(F_X(a^-)\) is the left-hand limit of the CDF.

### (a) Find \(P(X<1/2)\)

Since

$$
\frac13\le\frac12<\frac23,
$$

we use

$$
F_X(x)=\frac{3x+1}{6}.
$$

Because \(1/2\) lies inside this interval, the CDF is continuous there. Thus

$$
P(X<1/2)=F_X(1/2).
$$

Therefore

$$
P(X<1/2)
=
\frac{3(1/2)+1}{6}
=
\frac{5/2}{6}
=
\boxed{\frac5{12}}.
$$

### (b) Find \(P(X<2/3)\)

Now \(2/3\) is a point where the CDF changes formula.

We need the **left-hand limit**:

$$
P(X<2/3)
=
F_X\left(\left(\frac23\right)^-\right).
$$

For \(x<2/3\),

$$
F_X(x)=\frac{3x+1}{6}.
$$

Therefore

$$
P(X<2/3)
=
\frac{3(2/3)+1}{6}
=
\frac3{6}
=
\boxed{\frac12}.
$$

Notice that

$$
F_X(2/3)=\frac23,
$$

so there is a jump of

$$
\frac23-\frac12=\frac16.
$$

Hence

$$
P(X=2/3)=\frac16.
$$

### (c) Is \(X\) continuous?

No.

A continuous random variable must satisfy

$$
P(X=a)=0
$$

for every single point \(a\).

Here,

$$
P(X=2/3)=\frac16>0.
$$

Therefore,

$$
\boxed{X\text{ is not a continuous random variable}.}
$$

It has a discrete point mass at \(x=2/3\), even though its CDF contains continuous pieces.




---

# 5. Question

**CDF & PDF**

The probability density function (PDF) of a random variable has the following form:

$$
f(x)=
\begin{cases}
a, & x<0,\\
x, & x\in[0,1],\\
b(1-x), & x\in(1,2],\\
c, & x>2.
\end{cases}
$$

Here, \(a,b,c\) are constants.

**(a)** What are the values of \(a\), \(b\), and \(c\)?

**(b)** Compute the CDF corresponding to this PDF.

### Solution

A PDF must satisfy two conditions:

1. \(f(x)\ge0\) for every \(x\).
2. The total area under the PDF must be 1:

$$
\int_{-\infty}^{\infty}f(x)\,dx=1.
$$

### (a) Find \(a,b,c\)

#### Step 1: Find \(a\)

For \(x<0\),

$$
f(x)=a.
$$

If \(a>0\), then

$$
\int_{-\infty}^{0}a\,dx=\infty,
$$

which is impossible for a PDF.

Therefore,

$$
\boxed{a=0}.
$$

#### Step 2: Find \(c\)

For \(x>2\),

$$
f(x)=c.
$$

If \(c>0\), then

$$
\int_2^\infty c\,dx=\infty,
$$

which is impossible for a PDF.

Therefore,

$$
\boxed{c=0}.
$$

#### Step 3: Find \(b\)

The total area must equal 1:

$$
\int_0^1x\,dx
+
\int_1^2b(1-x)\,dx
=1.
$$

First,

$$
\int_0^1x\,dx
=
\left[\frac{x^2}{2}\right]_0^1
=
\frac12.
$$

For the second integral,

$$
\int_1^2b(1-x)\,dx
=
b\left[x-\frac{x^2}{2}\right]_1^2.
$$

Therefore,

$$
\int_1^2b(1-x)\,dx
=
-\frac b2.
$$

Hence,

$$
\frac12-\frac b2=1.
$$

Multiplying by 2,

$$
1-b=2.
$$

Thus,

$$
\boxed{b=-1}.
$$

This is valid because

$$
b(1-x)=-(1-x)=x-1,
$$

and \(x-1\ge0\) for \(1<x\le2\).

Therefore the PDF can be written more simply as

$$
\boxed{
f(x)=
\begin{cases}
0, & x<0,\\
x, & 0\le x\le1,\\
x-1, & 1<x\le2,\\
0, & x>2.
\end{cases}}
$$

So,

$$
\boxed{a=0,\qquad b=-1,\qquad c=0}.
$$

### (b) Find the CDF

The CDF is

$$
F_X(x)=P(X\le x)
=
\int_{-\infty}^{x}f(t)\,dt.
$$

#### Case 1: \(x<0\)

Since the PDF is zero before 0,

$$
\boxed{F_X(x)=0}.
$$

#### Case 2: \(0\le x\le1\)

Here \(f(t)=t\), so

$$
F_X(x)
=
\int_0^x t\,dt
=
\left[\frac{t^2}{2}\right]_0^x.
$$

Therefore,

$$
\boxed{F_X(x)=\frac{x^2}{2}}.
$$

#### Case 3: \(1<x\le2\)

We first accumulate the probability from 0 to 1:

$$
\int_0^1t\,dt=\frac12.
$$

Then add the probability from 1 to \(x\):

$$
F_X(x)
=
\frac12+\int_1^x(t-1)\,dt.
$$

Now,

$$
\int_1^x(t-1)\,dt
=
\left[\frac{(t-1)^2}{2}\right]_1^x
=
\frac{(x-1)^2}{2}.
$$

Therefore,

$$
F_X(x)
=
\frac12+\frac{(x-1)^2}{2}.
$$

Hence,

$$
\boxed{
F_X(x)=\frac{1+(x-1)^2}{2}
}.
$$

#### Case 4: \(x>2\)

The entire probability has been accumulated:

$$
\boxed{F_X(x)=1}.
$$

### Final CDF

Therefore,

$$
\boxed{
F_X(x)=
\begin{cases}
0, & x<0,\\[4pt]
\dfrac{x^2}{2}, & 0\le x\le1,\\[6pt]
\dfrac{1+(x-1)^2}{2}, & 1<x\le2,\\[6pt]
1, & x>2.
\end{cases}}
$$

### Quick check

At \(x=1\),

$$
F_X(1)=\frac12.
$$

At \(x=2\),

$$
F_X(2)
=
\frac{1+(2-1)^2}{2}
=
1.
$$

So the CDF correctly increases from 0 to 1.

---

# 6. Question

A positive integer is selected, with

$$
P(I=n)=\frac{1}{2^n},\qquad n=1,2,\ldots.
$$

If \(I\) takes the value \(n\), a coin with probability of heads equal to \(e^{-n}\) is tossed once. Find the probability that the resulting toss will be a head.

### Solution

Use the law of total probability.

Condition on \(I=n\):

$$
P(H\mid I=n)=e^{-n}.
$$

Also,

$$
P(I=n)=\frac1{2^n}.
$$

Therefore

$$
P(H)
=
\sum_{n=1}^{\infty}
P(H\mid I=n)P(I=n).
$$

Hence

$$
P(H)
=
\sum_{n=1}^{\infty}
e^{-n}\frac1{2^n}
=
\sum_{n=1}^{\infty}
\left(\frac1{2e}\right)^n.
$$

This is a geometric series with ratio

$$
r=\frac1{2e}.
$$

Therefore,

$$
P(H)
=
\frac{\frac1{2e}}{1-\frac1{2e}}
=
\boxed{\frac1{2e-1}}.
$$




---

# 7. Question

\(X\) is a strictly positive discrete random variable, i.e., it takes values in the set \(\{1,2,\ldots\}\), and \(p_X(x)\) is its PMF.

If the PMF has the form

$$
p_X(x)=C\frac{2^x}{x!},
$$

find the value of \(C\).

Repeat for

$$
p_X(x)=C\frac{2^{-x}}{x},
$$

and

$$
p_X(x)=Cx^\alpha.
$$

### Solution

Since \(X\) takes values \(1,2,\ldots\), a PMF must satisfy

$$
\sum_{x=1}^{\infty}p_X(x)=1.
$$

### Case 1

$$
p_X(x)=C\frac{2^x}{x!}.
$$

Therefore

$$
C\sum_{x=1}^{\infty}\frac{2^x}{x!}=1.
$$

Recall

$$
e^2=\sum_{x=0}^{\infty}\frac{2^x}{x!}.
$$

Removing the \(x=0\) term gives

$$
\sum_{x=1}^{\infty}\frac{2^x}{x!}=e^2-1.
$$

Hence

$$
\boxed{C=\frac1{e^2-1}}.
$$

### Case 2

$$
p_X(x)=C\frac{2^{-x}}{x}.
$$

We need

$$
C\sum_{x=1}^{\infty}\frac{(1/2)^x}{x}=1.
$$

Using

$$
\sum_{x=1}^{\infty}\frac{z^x}{x}
=
-\ln(1-z),
\qquad |z|<1,
$$

with \(z=1/2\),

$$
\sum_{x=1}^{\infty}\frac{2^{-x}}{x}
=
-\ln\left(1-\frac12\right)
=
\ln2.
$$

Therefore

$$
\boxed{C=\frac1{\ln2}}.
$$

### Case 3

$$
p_X(x)=Cx^\alpha.
$$

We need

$$
C\sum_{x=1}^{\infty}x^\alpha=1.
$$

The series converges only when

$$
\alpha<-1.
$$

Using the Riemann zeta function,

$$
\zeta(s)=\sum_{x=1}^{\infty}\frac1{x^s},
$$

we have

$$
\sum_{x=1}^{\infty}x^\alpha
=
\zeta(-\alpha).
$$

Therefore

$$
\boxed{
C=\frac1{\zeta(-\alpha)},
\qquad \alpha<-1.
}
$$

For \(\alpha\ge-1\), no positive normalizing constant \(C\) exists, because the series diverges.




---

# 8. Question

For the previous problem, find:

**(i)** \(P(X>2)\)

**(ii)** the most probable value of \(X\).

> **Interpretation:** Since Question 7 contains three different PMFs, the solution below treats Question 8 for **each of the three distributions**.

### Solution

Question 7 contains three different PMFs, so we solve this for each one.

## Distribution 1

$$
p_X(x)=\frac1{e^2-1}\frac{2^x}{x!},
\qquad x=1,2,\ldots
$$

### (i) Find \(P(X>2)\)

We need

$$
P(X>2)
=
1-P(X=1)-P(X=2).
$$

Now

$$
P(X=1)
=
\frac{2}{e^2-1},
$$

and

$$
P(X=2)
=
\frac{4/2}{e^2-1}
=
\frac{2}{e^2-1}.
$$

Therefore

$$
P(X>2)
=
1-\frac4{e^2-1}
=
\boxed{\frac{e^2-5}{e^2-1}}.
$$

### (ii) Most probable value

Compare consecutive probabilities:

$$
\frac{p_X(x+1)}{p_X(x)}
=
\frac{2}{x+1}.
$$

This ratio is greater than 1 when \(x<1\), equal to 1 when \(x=1\), and less than 1 for \(x>1\).

Therefore the probabilities are maximized at

$$
\boxed{x=1,2}.
$$

So the distribution is bimodal with modes 1 and 2.

---

## Distribution 2

$$
p_X(x)=\frac1{\ln2}\frac{2^{-x}}x,
\qquad x=1,2,\ldots
$$

### (i) Find \(P(X>2)\)

$$
P(X>2)
=
1-P(X=1)-P(X=2).
$$

We have

$$
P(X=1)=\frac1{2\ln2},
$$

and

$$
P(X=2)=\frac1{4\ln2}.
$$

Therefore

$$
\boxed{
P(X>2)
=
1-\frac{3}{4\ln2}
}.
$$

### (ii) Most probable value

For \(x\ge1\),

$$
\frac{p_X(x+1)}{p_X(x)}
=
\frac{x}{2(x+1)}<1.
$$

Therefore the PMF decreases from \(x=1\).

Hence the most probable value is

$$
\boxed{x=1}.
$$

---

## Distribution 3

$$
p_X(x)=Cx^\alpha,
\qquad \alpha<-1,
$$

where

$$
C=\frac1{\zeta(-\alpha)}.
$$

### (i) Find \(P(X>2)\)

$$
P(X>2)
=
\sum_{x=3}^{\infty}Cx^\alpha.
$$

Therefore

$$
\boxed{
P(X>2)
=
\frac{\zeta(-\alpha)-1-2^\alpha}
{\zeta(-\alpha)}
}.
$$

Equivalently,

$$
\boxed{
P(X>2)
=
1-\frac{1+2^\alpha}{\zeta(-\alpha)}
}.
$$

### (ii) Most probable value

Since \(\alpha<-1\),

$$
x^\alpha
$$

decreases as \(x\) increases.

Therefore the largest probability occurs at \(x=1\):

$$
\boxed{x=1}.
$$




---

# 9. Question

There are \(n\) coins, each of which comes up heads with probability \(p\). In round 1, each coin is tossed once. In round 2, all those coins that came up heads in round 1 are tossed again and others are left unchanged.

Let \(X\) be the total number of heads after round 2. Find the PMF of \(X\).

### Solution

Let

$$
H_1
$$

be the number of heads after round 1.

Since each of the \(n\) coins independently gives heads with probability \(p\),

$$
H_1\sim\operatorname{Binomial}(n,p).
$$

Suppose

$$
H_1=h.
$$

Then:

- \(h\) coins showed heads in round 1 and are tossed again.
- \(n-h\) coins showed tails and remain tails.

Let \(Y\) be the number of heads among those \(h\) coins in round 2.

Conditional on \(H_1=h\),

$$
Y\mid H_1=h\sim\operatorname{Binomial}(h,p).
$$

The final number of heads is

$$
X=h+Y.
$$

Therefore, for \(x=0,1,\ldots,n\),

$$
P(X=x)
=
\sum_{h=0}^{x}
P(H_1=h)P(Y=x-h\mid H_1=h).
$$

Substitute the binomial probabilities:

$$
P(X=x)
=
\sum_{h=0}^{x}
\binom nh
p^h(1-p)^{n-h}
\binom h{x-h}
p^{x-h}(1-p)^{h-(x-h)}.
$$

The valid values of \(h\) must also satisfy

$$
0\le x-h\le h,
$$

so

$$
\left\lceil\frac{x}{2}\right\rceil\le h\le x.
$$

Thus the PMF is

$$
\boxed{
P(X=x)
=
\sum_{h=\lceil x/2\rceil}^{x}
\binom nh
\binom h{x-h}
p^x
(1-p)^{n-2h+x}
},
\qquad x=0,\ldots,n.
$$

An equivalent expression is obtained by conditioning on the number \(h\) of first-round heads.




---

# 10. Question

Let \(X\) be the random variable denoting the number of tosses of a biased coin to get the first head. The first head has not occurred in the first \(k\) tosses. What is the probability that you will have to toss the coin \(n\) more times?

### Solution

Let the probability of a head be

$$
p,
$$

so the probability of a tail is

$$
q=1-p.
$$

We are told that the first head has **not** occurred in the first \(k\) tosses.

This means that the first \(k\) tosses were all tails.

Because coin tosses are independent, the future tosses are independent of those first \(k\) tosses.

Therefore the conditional distribution of future tosses is unchanged.

If "you will have to toss the coin \(n\) more times" means that the first head occurs exactly on the \(n\)-th additional toss, then the first \(n-1\) additional tosses must be tails and the \(n\)-th must be a head.

Thus

$$
P(\text{first head occurs on next }n\text{ tosses}\mid T_1,\ldots,T_k)
=
q^{n-1}p.
$$

Therefore,

$$
\boxed{
P(\text{first head occurs on the }n\text{-th additional toss})
=
(1-p)^{n-1}p
}.
$$

The fact that the first \(k\) tosses were tails does not change this probability.

> **Note:** If the intended wording "toss the coin \(n\) more times" means **at least \(n\) additional tosses are required before seeing a head**, then the answer would instead be
>
> $$
> \boxed{(1-p)^{n}}.
> $$
>
> The usual interpretation of a geometric waiting-time question is that the first head occurs on the \(n\)-th additional toss, giving \(p(1-p)^{n-1}\).

