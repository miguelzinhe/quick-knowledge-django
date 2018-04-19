# Quick things about Templates in Django

### Context
A template can have variable names in double curly braces, such as {{ myvar1 }}, {{ myvar2 }}. So context is a dictonary with variable names. 
 
### `myproject/home/views.py`
```python

def index(request):
    return render(request, 'home.html', {'usuario': 'miguel'})
```
 
