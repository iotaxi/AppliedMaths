---  
layout: post  
---  
Day 8   
Stars and Bars is an approach that is sometimes useful when dealing with combinations where repetitions are allowed. In these problems, some objects are identical and some are distinct.  

We may wish to count the number of ways there are to put $$k$$ indistinguishable balls into $$n$$ distinguishable urns. The $$k$$ balls are represented by $$k$$ stars and the $$n$$ urns are represented by $$n-1$$ bars. The bars are placed between the stars. We can place multiple bars between stars, before the first star and after the last star.  
This technique allows us to conclude that the answer is given by $${n+k-1 \choose k}$$ or equivalently by $${n+k-1 \choose n-1}$$     
  
Suppose we may wish to count the number of ways there are to put $$7$$ indistinguishable balls into $$5$$ distinguishable urns.  
Consider this graphic:  
\*\*\*\*\|\|\*\|\*\*\|  
This represents the situation where we have 7 balls and 5 urns.  
In the first urn, there are 4 balls. In the second urn, there are 0 balls. In the third urn, there is 1 ball.      
In the fourth urn, there are 2 balls. In the fifth urn, there are 0 balls.      
We may interpret \|\*\*\|\*\*\*\|\*\*\| or \*\|\*\|\|\*\*\*\|\*\*    
The problem now is to calculate the number of ways that we can place the 7 stars in the 11 available spaces and that is $${11 \choose 7}$$  
But $$11=5+7-1$$.
We conclude that the number of ways there are to put $$7$$ indistinguishable balls into $$5$$ distinguishable urns is $${5+7-1 \choose 7}$$  
Similarly, we may deduce that the number of ways there are to put $$k$$ indistinguishable balls into $$n$$ distinguishable urns is $${n+k-1 \choose k}$$  

After Day 8, our take away message is:  
The number of ways there are to put $$k$$ indistinguishable balls into $$n$$ distinguishable urns is given by:  

  
<span style="color:blue">$${n+k-1 \choose k}$$ or $${n+k-1 \choose n-1}$$</span>       
