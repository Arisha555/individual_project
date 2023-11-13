# individual_project

```python
from random import random
import matplotlib.pyplot as plt

x = []
y = []
for i in range(100):
    s = random() * (5 + 5) - 5
    x.append(s)
for i in range(100):
    r = random() * (5 + 5) - 5
    y.append(r)

plt.scatter(x, y)
plt.show()
```

```python
import matplotlib.pyplot as plt
import math

x = []
y = []
for i in range(-50, 50):
    t = i / 10
    if t != -1:
        x.append(t)
        y.append(math.sin(1 / (t + 1)))
plt.plot(x, y)
plt.show()
```
