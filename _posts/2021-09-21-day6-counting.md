---
layout: post
topic: counting
---
Day 6  
Multinomials  
n objects, k gps, sizes $$a_{1},a_{2},\ldots a_{k}$$ so that $$ a_{1}+\ldots+a_{k}=n$$.  
  
There are $${n \choose a_{1}}$$ ways of forming the first gp.  
When that has been done, there are $${n-a_{1} \choose a_{2}}$$ ways of forming the second gp so there are $${n \choose a_{1}}{n-a_{1} \choose a_{2}}$$ ways of forming the first two gps.  
The number of ways of forming all the gps is:    

$${n \choose a_{1}}{n-a_{1} \choose a_{2}}\cdots\cdots{n-a_{1}-a_{2}-\cdots\cdots a_{k-1} \choose a_{k}}$$

$$=\frac{n!}{a_{1}!(n-a_{1})!}\frac{(n-a_{1})!}{a_{2}!(n-a_{1}-a_{2})!}\cdots\cdots\frac{(n-a_{1}-\cdots\cdots a_{k-1})}{a_{k}(1!)}$$

$$=\frac{n!}{a_{1}!a_{2}!a_{3}!\cdots\cdots a_{k}!}$$

Notation

$${n \choose a_{1},a_{2},\cdots\cdots a_{k}}=\frac{n!}{a_{1}!a_{2}!a_{3}!\cdots\cdots a_{k}!}$$

Use this for:

n objects, k gps, of sizes $$a_{1},a_{2,}..a_{k}$$

anagrams of MISSISSIPPI  

not for anagrams of LYX  

After Day 4, our take away message is:  
<span style="color:blue">$${n \choose a_{1},a_{2},\ldots,n_{k}}=\frac{n!}{a_{1}!\times a_{2}!\times\cdots\times a_{k}!}$$</span>  
