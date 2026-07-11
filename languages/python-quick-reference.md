# مرجع سريع للغة Python

## الأساسيات
```python
# متغيرات وأنواع
 x = 5          # int
 y = 3.14       # float
 s = "text"     # str
 lst = [1,2,3]  # list
 d = {"a":1}    # dict
 t = (1,2)      # tuple
 st = {1,2,3}   # set
```

## التحكم في التدفق
```python
if condition:
    ...
elif other:
    ...
else:
    ...

for item in iterable:
    ...

while condition:
    ...
```

## الدوال والكلاسات
```python
def greet(name: str) -> str:
    return f"Hello {name}"

class Agent:
    def __init__(self, name):
        self.name = name
    def act(self):
        return f"{self.name} is acting"
```

## أفضل المكتبات لمشاريع AI Agent
- `requests` — استدعاءات HTTP
- `pydantic` — التحقق من البيانات
- `fastapi` — بناء API سريع
- `langchain` / `llama-index` — بناء وكلاء ذكية
- `pandas` — معالجة البيانات الجدولية
