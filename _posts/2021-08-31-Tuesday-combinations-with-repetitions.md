---
---
Combinations with repetitions.

How many groups of n objects taken k at a time may be made if repetitions are allowed?

The solution is $${n+k-1 \choose k}$$ or $${n+k-1 \choose n-1}$$ .

To solve these, we must picture the situation.

Suppose you want to distribute 15 ham sandwiches to eight people, with no restriction on how many each person gets. How many ways are there of choosing how many sandwiches each person gets?

The answer is $${8+15-1 \choose 8-1}$$ or $${8+15-1 \choose 15}$$ .

So the problem reduced to n=8 and k=15.

Why is this?

Stars and Bars

This is the same as finding all the non negative integral solutions to $$a+b+c+d+e+f+g+h=15$$

The stars and bars approach is based on 15 stars and 7 bars so the answer is $${15+7 \choose 7}$$ or equivalently $${15+7 \choose 15}$$

Also follow up on multinomials such as $$\frac{n!}{a_1! \times a_2! \times \cdots \times a_k!}$$ which may also be written as $$\binom{n}{a_1, a_2, \ldots , n_k}$$.
