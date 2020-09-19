[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

Approximately 34% of men are in the range of 5'10" to 6'1."

```python
shorter_m = scipy.stats.norm.cdf(177.8, 178, 7.7)
taller_m = scipy.stats.norm.cdf(185.4, 178, 7.7)
taller_m-shorter_m
```

By contrast only 2% of women fall into this same range.

```python
shorter_f = scipy.stats.norm.cdf(177.8, 163, 7.3)
taller_f = scipy.stats.norm.cdf(185.4, 163, 7.3)
taller_f-shorter_f
```

