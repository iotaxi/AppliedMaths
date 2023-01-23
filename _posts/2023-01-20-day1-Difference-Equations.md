---
layout: post
topic: counting

---
Day 1

Difference Equations// 
$${P_{n+1}}=1.052 {P_n}-3000\$$is a difference equation $$where\:𝑛\geq0,\:𝑛∈\mathbb{Z\:}and\:𝑃_{0}=150,000.$$//

(i) Solve this difference equation to find an expression for $${P_{n}} in terms of \(𝑛$$.

In this difference equation, reference is made to one previous term, so ITERATION should work.

Write down the first term, then the second term and so on to see a pattern.

Simplify as you go.Write each term as a function of \(\:𝑃_{0}.\) Do not evaluate numbers such as \(4^2\).

$$P_{1}=1.052P_{0}-3000$$
$$P_{2}=1.052\,P_{1}-3000=1.052(1.052P_{0}-3000)=1.052^{2}P_{0}-1.052(3000)$$

$$P_{2}=1.052\,P_{1}-3000=1.052(1.052P_{0}-3000)=1.052^{2}P_{0}-(1.052)(3000)$$
$$P_{3}=1.052\,P_{2}-3000=1.052((1.052^{2}P_{0}-(1.052)(3000))-3000)=1.052^{3}P_{0}-(1.052^{2})(3000)-(1.052)(3000)$$
and so on. We now deduce:
$$P_{n}=1.052^{n}P_{0}-(1.052^{n-1})(3000)-(1.052^{n-2})(3000)\cdots\cdots-(1.052)(3000)$$
$$P_{n}=1.052^{n}P_{0}-(1.052)(3000)(1.052^{n-2}+1.052^{n-3}\cdots\cdots+1)$$
$$P_{n}=1.052^{n}P_{0}-(1.052)(3000)(1+1.052^{1}+1.052^{2}+\cdots\cdots+1.052^{n-2})$$
This equation includes a geometric series of n-1 terms with first term 1 and common ratio 1.052.
$$P_{n}=1.052^{n}P_{0}-(1.052)(3000)(\frac{1(1-1.052^{n-1})}{1-1.052})$$
$$P_{n}=1.052^{n}P_{0}+(60692.308)(1-1.052^{n-1})$$
$$P_{n}=(1.052^{n})(150000)-(1.052)(3000)(\frac{1(1-1.052^{n-1})}{1-1.052}$$
$$P_{n}=(1.052^{n})(150000)+(60692.308)(1-1.052^{n-1})$$
 
