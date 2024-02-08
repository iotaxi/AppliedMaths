---
layout: post
topic: counting
---

	load (descriptive)$  
	load (distrib)$  
	fpprintprec : 6$  
	ratprint : false$  
	  
	for k:0 thru 15 do (qq:float (cdf_poisson(k,15)), print([k,qq,quantile_poisson(qq,15)]))$  

  
<img src="/assets/images/woollettquantilepoissonscreenshot08022024.jpg" alt="">  