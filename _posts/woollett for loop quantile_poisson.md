---
layout: post
topic: counting
---

	load (descriptive)$  
	load (distrib)$  
	fpprintprec : 6$  
	ratprint : false$  
	  
	for k:0 thru 15 do (qq:float (cdf_poisson(k,15)), print([k,qq,quantile_poisson(qq,15)]))$  

![image](/assets/images/woollett quantile_poisson screenshot 2024-02-08 205122.jpg)  
<img src="/assets/images/woollett quantile_poisson screenshot 2024-02-08 205122.jpg" alt="">  