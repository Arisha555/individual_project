# individual_project
from random import random
import matplotlib.pyplot as plt

```python
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
