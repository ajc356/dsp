[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

Weight:

`print("Average weight of first babies:", firsts.totalwgt_lb.mean())`  
`print("Average weight of 'others'/non-first babies:", others.totalwgt_lb.mean())`  
`print("Difference between groups:", CohenEffectSize(firsts.totalwgt_lb, others.totalwgt_lb))`  

Pregnancy Length:

`print("Average pregnancy length of first babies:", firsts.prglngth.mean())`  
`print("Average pregnancy length of 'others'/non-first babies:", others.prglngth.mean())`  
`print("Difference between groups:", CohenEffectSize(firsts.prglngth, others.prglngth))`  



The difference between average weight of first babies and non-first babies is relatively small, -0.089 which suggests first babies are maginally smaller than others.   The difference between average pregnancy length in first babies and non-first babies is also relatively small, 0.029 which suggests first babies have a marginally longer pregnancy length than others. 

