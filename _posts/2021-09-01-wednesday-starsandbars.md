---
---

Wednesday. Combinations of n objects taken k at a time where repetitions are allowed.

Stars and Bars (William Feller) may be used to count the number of ways there are to put n indistinguishable balls into k distinguishable bins.

In these problems, some objects are identical and some are distinct.

Suppose n=10 and k=4. The answer is the number of solutions to $$x_{1}+x_{2}+x_{3}+x_{4}=10$$

where$$x_{1},x_{2},x_{3},x_{4}\geq0$$.The situation where$$x_{1},x_{2},x_{3},x_{4}>0$$is different. The answer is given by$${n+k-1 \choose k-1}={10+4-1 \choose 4-1}={13 \choose 3}=286$$

The n objects are represented by stars.$$k-1$$bars are place between the stars. We can place multiple bars between stars, before the first star and after the last star.  
st st st st ||st |st st |  
means  
four bars give rise to five bins containing 4, 0, 1, 2, and 0 objects.
