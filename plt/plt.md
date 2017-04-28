

```python
# import matplotlib
# matplotlib.use('Agg') # Must be before importing matplotlib.pyplot or pylab!
import matplotlib.pyplot as plt
# %matplotlib inline
```


```python
year = [1950, 1970, 1990, 2010]
population = [2.519, 3.692, 5.263, 6.972]
# year is x and population is y
# plot shows what to plot and how to plot
plt.plot(year, population)
```




    [<matplotlib.lines.Line2D at 0x10dfc96d8>]




```python
# plots
plt.show()
```


![png](output_2_0.png)



```python
# Scatter plot
plt.scatter(year, population)
plt.show()
```


![png](output_3_0.png)



```python

```
