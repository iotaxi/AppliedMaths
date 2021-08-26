---
---
Able to Display Equations on Jekyll Site  
Step1: went to jekyllrb to docs to themes and overiding theme defaults  
Step2: used git bash terminal and explorer to upload Minima hidden from view folders to Github.com  
Step3: went to LaTex in Jekyll by Ian Goodfellow as http://www.iangoodfellow.com/blog/jekyll/markdown/tex/2016/11/07/latex-in-markdown.html  
Step4: added MathJax, a JavaScript library that does the actual rendering, by modifying post.html.  
The added code is <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
Outcome  
$$ x = y^2 $$  
$$ x = y^3 $$  
$$ \nabla_\boldsymbol{x} J(\boldsymbol{x}) $$  
The markdown syntax uses $ one more time in each delimiter to the Latex Code giving double $ at each delimiter 
