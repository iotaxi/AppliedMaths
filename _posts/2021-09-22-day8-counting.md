---  
layout: post  
---  

Day 8   
Stars and Bars is an approach that is sometimes useful when dealing with combinations where repetitions are allowed.  
In these problems, some objects are identical and some are distinct.

We wish to count the number of ways there are to put $$k$$ indistinguishable balls into $$n$$ distinguishable bins. 
The $$k$$ balls are represented by stars and $$n-1$$ bars are placed between the stars.
The answer is given by $${n+k-1 \choose n-1}$$  or equivalently by $${n+k-1 \choose k}$$  

Consider this graphic:  
\*\*\*\*\|\|\*\|\*\*\|  
We can place multiple bars between stars, before the first star and after the last star.  
This represents a situation where we have 7 balls and 5 urns.  
In the first urn, there are 4 balls.   
In the second urn, there are 0 balls.    
In the third urn, there is 1 ball.    
In the fourth urn, there are 2 balls    
In the fifth urn, there are 0 balls.    
