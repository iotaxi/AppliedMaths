---
layout: post
topic: counting
---  
The Maxima function quantile_binomial (q,n,p) returns the q-quantile of a Binomial(n,p) random variable.  
This is the inverse of cdf_binomial. Argument q must be an element of [0,1].  
    
Calculations with ordinary floats always use all their digits (16 or so), and fpprec has no effect on that.  
Calculations with bigfloats do make use of fpprec.  
When p is a rational, values for the pdf and cdf of a binomial distribution are going to be rationals  
  
 Using rationals instead of floats appears to cure the problem:  
(%i20)	my_quantile_binomial (qq, nn, pp) :=   
quantile_binomial (rat(qq), rat(nn), rat(pp))$  
see Wednesdaywoollett@charter.net on 24012024  

