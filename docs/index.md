# Homepage 

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Code Anotation Examples

### Codeblocks

Some code `code` goes here

### A plain code block

a plain code block:

```
def sphere_surface_area(radius):  
    """
    Calculates the surface area of a sphere given its radius.  
    """  
    pi = 3.14159   
    return 4 * pi * radius ** 2  
```

###  now the same with an additional "py" after the 3 back ticks

``` py
def sphere_surface_area(radius):  
    """
    Calculates the surface area of a sphere given its radius.  
    """  
    pi = 3.14159   
    return 4 * pi * radius ** 2  
```

### The same with a program title
other text


``` py title="sphere_surface.py"
def sphere_surface_area(radius):  
    """
    Calculates the surface area of a sphere given its radius.  
    """  
    pi = 3.14159   
    return 4 * pi * radius ** 2  
```

### The same with a line numbers

comment

``` py linenums="1" title="sphere_surface.py"
def sphere_surface_area(radius):  
    """
    Calculates the surface area of a sphere given its radius.  
    """  
    pi = 3.14159   
    return 4 * pi * radius ** 2  
```

### The highlight limes 
comment
``` py hl_lines="5 6" linenums="1" title="sphere_surface.py"
def sphere_surface_area(radius):  
    """
    Calculates the surface area of a sphere given its radius.  
    """  
    pi = 3.14159
    print(pi)
    return 4 * pi * radius ** 2  
```


