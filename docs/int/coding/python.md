---
tags:
    - Py
    - Python
    - Code
    - Codar
---

##Criação em python


```py title="Formula Matemática com Baskara" linenums="1"

import math

def bhaskara(a, b, c):
    delta = b**2 - 4*a*c
    print(f"Delta: {delta}")
    
    if delta < 0:
        print("Não existem raízes reais.")
    elif delta == 0:
        x = -b / (2*a)
        print(f"Raiz única: x = {x}")
    else:
        x1 = (-b + math.sqrt(delta)) / (2*a)
        x2 = (-b - math.sqrt(delta)) / (2*a)
        print(f"Duas raízes reais: x1 = {x1}, x2 = {x2}")
```

### **Exemplo de uso**
a = 1

b = -3

c = 2

bhaskara(a, b, c)