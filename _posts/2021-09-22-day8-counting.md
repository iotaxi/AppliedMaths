---  
layout: post  
---  

Day 8  

Stars and Bars  

see starsandbarsSatblog04092021.lyx  

Suppose you want to distribute 15 identical balls among eight distinguishable urns, with no restriction on how many in each urn. How many ways are there of choosing how balls in each urn?

Picture one outcome: 3 balls in first urn, 0,0,0,0,0,7,5 ballsin eight urn.

Stars and Bars: s s s \| \| \| \| \| \| s s s s s s s \| s s s s s , which is 15 stars and 7 bars.

Number of ways is: $${n+k-1 \choose n-1}={15+7 \choose 7}={22 \choose 7}$$

Both $${n+k-1 \choose n-1}$$ and $${n+k-1 \choose k-1}$$ may be used. In the first case k is 15 and in the second case n is 15.  
---  
layout: post  
---  
see starsandbarswednesday01092021.lyx  

Wednesday.  
Combinations of n objects taken k at a time where repetitions are allowed.

Stars and Bars (William Feller) may be used to count the number of ways there are to put n indistinguishable balls into k distinguishable bins.

In these problems, some objects are identical and some are distinct.

Suppose n=10 and k=4. The answer is the number of solutions to $$x_{1}+x_{2}+x_{3}+x_{4}=10$$

where $$x_{1},x_{2},x_{3},x_{4}\geq0$$. The situation where $$x_{1},x_{2},x_{3},x_{4}>0$$ is different. The answer is given by $${n+k-1 \choose k-1}={10+4-1 \choose 4-1}={13 \choose 3}=286$$  

The n objects are represented by stars. $$k-1$$ bars are place between the stars. We can place multiple bars between stars, before the first star and after the last star.

\*\*\*\*\|\|\*\|\*\*\|

means

four bars give rise to five bins containing 4, 0, 1, 2, and 0 objects.  
---  
layout: post  
---   
see starsandbarsthursday02092021    

Thursday More Stars than Bars and More Bars than Stars

The case where $$x_{1,}x_{2},...>0$$ is denoted by SAB1

The case where $$x_{1,}x_{2},...\geq0$$ is denoted by SAB2

SAB2 allows for more bars than stars.

In how many ways can 7 balls be placed in 10 bins?

7 balls means 7 stars and 10 bins means 9 bars so the solu is $${n+k-1 \choose k-1}={7+9 \choose 9}={16 \choose 9}$$

In how many ways can 10 balls be placed in 7 bins?

10 balls means 10 stars and 7 bins means 6 bars so the solu is $${n+k-1 \choose k-1}={10+6 \choose 6}={16 \choose 6}$$
