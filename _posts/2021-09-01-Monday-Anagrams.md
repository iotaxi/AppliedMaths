---
layout: post
---
Monday  
Counting and Anagrams  
MISSISSIPPI  
M  
IIII  
SSSS  
PP  
How many anagrams are possible using all letters and assuming that like letters are identical?  
These problems are easier if we think think graphically. Imagine that you are actually making   
an arrangement of the letters. In other words, think physically. So we imagine a rack and cards.  
Suppose we have a straight rack with 11 card slots and that the 11 letters are printed on cards which may be placed in the card slots in the rack.  

$$\square\square\square\square\square\square\square\square\square\square\square$$

The four identical letters S may be placed on this rack in $${11 \choose 4}$$ different ways.  

When this has been done, the four identical letters I may be placed on this rack in $${7 \choose 4}$$ different ways.  

By the principle of multiplication, the number of ways of performing both of these operations is  

$${11 \choose 4}{7 \choose 4}$$

When this has been done, the number of ways of distributing the two letters P is $${3 \choose 2}$$  

The number of ways of performing these three operations is  

$${11 \choose 4}{7 \choose 4}{3 \choose 2}$$

When all of this has been done, the number of ways of distributing the one remaining letter M in the one remaining space is $${1 \choose 1}$$  

The number of anagrams using all letters of MISSISSIPPI and assuming that like letters are identical is  

$${11 \choose 4}{7 \choose 4}{3 \choose 2}{1 \choose 1}$$

Confirm for yoursef that you get the same answer if you start by distributing the two letters P and then the M is  
$${11 \choose 2}{9 \choose 1}{8 \choose 4}{4 \choose 4}$$  

But  

$${11 \choose 4}{7 \choose 4}{3 \choose 2}{1 \choose 1}=\frac{11!}{4!4!2!1!}$$

The number of anagrams of  
M  
IIII  
SSSS  
PP  
is the multinomial  
$$\frac{11!}{4!4!2!1!}$$

Recall that the number of anagrams of FRACTION is an easy problem.  
$$\square\square\square\square\square\square\square\square$$  

The first place may be filled in 8 ways and then the second place in 7 ways and so on to yield

$$8!$$

There is no need to use the multinomial, but it would yield

$$\frac{8!}{1!1!1!1!1!1!1!1!}$$
