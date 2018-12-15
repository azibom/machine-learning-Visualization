# machine-learning-Visualization
Visualization in python

# Visualization
you can see a different kind of charts in this code but if you don't write it and don't run it you can't understand it
```python
import numpy as np
import matplotlib.pyplot as plt

A = [1, 2, 3, 4, 5]
B = [1, 2, 3, 4, 5]
labels = ['a', 'b', 'c', 'd', 'e']

# Line Plot
plt.plot(A, B)
plt.show()

# Scatter Plot
plt.scatter(A, B)
plt.show()

# Histogram Plot
plt.hist(A)
plt.show()

# Pie Chart
plt.pie(A, labels = labels)
plt.show()

```

## Customize Line Plot
#### labels
```python
plt.xlabel('Year')
plt.ylabel('Population')

some things like help
```python
plt.legend(['iran','Turkey'],loc='best')
```

#### colors
```python
plt.plot(A, B, color='green')
```

## Subplot
you can have two chart behind each other (let's try it)
```python
plt.subplot(1,2,1)
plt.plot(years, iran_pop)
plt.title('Iran Population')
plt.subplot(1,2,2)
plt.plot(years,turkey_pop)
plt.title('Turkey Population')
plt.show()
```

I hope this data will be useful to you.



