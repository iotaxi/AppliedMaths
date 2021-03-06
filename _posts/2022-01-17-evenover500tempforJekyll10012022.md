---
layout: post
topic: counting
---
# Comment for tex in Jekyll. Use double dollar for inline and display. Use blank line before and after for display. Do not use double blackslash. Use blank line instead  
Draw three boxes to represent an arbitrary three digit number, and then write in each box the number of digits that can be placed there\\
When there are restrictions, fill the restricted places first.

$$
\begin{array}{|c|l|c|r|}
\hline
\text{step 2} & \text{step 3} & \text{step 1} \\
\hline
  &  &  \\
\hline
\end{array}
$$

The first step is to indicate the number of choices for the units column.
The number is even so we place either a 2 or a 4 in the units column. We may fill this box in $$\binom{2}{1}$$ ways.
When this has been done, the second step is to fill the hundreds column. If a 4, for example, was placed in the units column, we could place either a 1 or a 2 or a 3 here. We may fill this box in $$\binom{3}{1}$$ ways.
When this has been done, the third step is to fill the tens column. If a 4, for example, was placed in the units column and a 3 was placed in the hundreds column, we could place either a 1 or a 2 or a 5  here. We may fill this box in $$\binom{3}{1}$$ ways.
   
$$
\begin{array}{|c|l|c|r|}
\hline
\text{step 2} & \text{step 3} & \text{step 1} \\
\hline
\binom{3}{1} & \binom{3}{1}  & \binom{2}{1}  \\
\hline
\end{array}
$$

By The Multiplication Principle, the number of ways of doing step1 and step 2 and step 3 is $$\binom{3}{1} \times \binom{3}{1} \times \binom{2}{1}$$. The number of three digit numbers is 3.3.2 =18.

Now draw two boxes to represent an arbitrary two digit number and then write in each box the number of digits that can be placed there.
Again fill the restricted places first.

$$
\begin{array}{|c|r|}
\hline
 \text{step 2} & \text{step 1} \\
\hline
\binom{4}{1}  & \binom{2}{1}  \\
\hline
\end{array}
$$

By The Multiplication Principle, the number of ways of doing step1 and step 2 is $$\binom{4}{1} \times \binom{2}{1}$$. There are 4.2=8 two digit numbers.

Next draw one box to represent an arbitrary one digit number, and then write in that box the number of digits that can be placed there.

$$
\begin{array}{|c|}
\hline
 \text{step 1} \\
\hline
\binom{2}{1}  \\
\hline
\end{array}
$$

As this is a restricted place, it can only be filled in $$ \binom{2}{1} $$ or 2 ways.

By The Addition Principle, the number of even numbers less than 500 is

$$\binom{3}{1} \times \binom{3}{1} \times \binom{2}{1} + \binom{4}{1} \times \binom{2}{1} + \binom{2}{1}= 18+8+2=28$$.









 
