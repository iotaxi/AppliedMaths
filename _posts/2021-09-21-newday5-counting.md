---
layout: post
topic: counting

---
Day 5

Binomial Coefficients  
$${n \choose k}={n \choose n-k}$$  
$${n \choose k}={n-1 \choose k}+{n-1 \choose k-1}$$  
$$(a+b)^{n}={n \choose 0}a^{n}+{n \choose 1}a^{n-1}b+\cdots+{n \choose n}b^{n}$$  
$${n \choose 0}=1={n \choose n}$$  
$$2^{n}={n \choose 0}+\cdots+{n \choose n}$$  
$$Pascals\bigtriangleup$$  

$$P_{1}=1.052P_{0}-3000$$
$$\P_{2}=1.052\,P_{1}-3000=1.052(1.052P_{0}-3000)=1.052^{2}P_{0}-1.052(3000)$$

\[P_{2}=1.052\,P_{1}-3000=1.052(1.052P_{0}-3000)=1.052^{2}P_{0}-(1.052)(3000)\]
\[P_{3}=1.052\,P_{2}-3000=1.052((1.052^{2}P_{0}-(1.052)(3000))-3000)=1.052^{3}P_{0}-(1.052^{2})(3000)-(1.052)(3000)\]
and so on. We now deduce:
\[P_{n}=1.052^{n}P_{0}-(1.052^{n-1})(3000)-(1.052^{n-2})(3000)\cdots\cdots-(1.052)(3000)\]
\[P_{n}=1.052^{n}P_{0}-(1.052)(3000)(1.052^{n-2}+1.052^{n-3}\cdots\cdots+1)\]
\[P_{n}=1.052^{n}P_{0}-(1.052)(3000)(1+1.052^{1}+1.052^{2}+\cdots\cdots+1.052^{n-2})\]
This equation includes a geometric series of n-1 terms with first term 1 and common ratio 1.052.
 \[P_{n}=1.052^{n}P_{0}-(1.052)(3000)(\frac{1(1-1.052^{n-1})}{1-1.052})\]
\[P_{n}=1.052^{n}P_{0}+(60692.308)(1-1.052^{n-1})\]
\[P_{n}=(1.052^{n})(150000)-(1.052)(3000)(\frac{1(1-1.052^{n-1})}{1-1.052}\]
\[P_{n}=(1.052^{n})(150000)+(60692.308)(1-1.052^{n-1})\]

After Day 4, our take away message is:  
<span style="color:blue">$${n \choose k}={n \choose n-k}$$</span>  
<span style="color:blue">$${n \choose k}={n-1 \choose k}+{n-1 \choose k-1}$$</span>  
