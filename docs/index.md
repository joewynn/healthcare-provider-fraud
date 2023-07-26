# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Code Annotation Examples

### Codeblocks

Some `code` for `py` here

```py
def add(a, b): 
    """
    Addition function 

    Inputs
    a (float): first number
    b (float): second number

    Return: 
    A multiplication of a and b (a*b)
    """
    return float(a*b)
```

#### with a title 

```py title="buble_sort.py"

def bubble_sort(items): 
    for i in range(len(items)): 
        for j in range(len(items) - 1 - i):
            if items[j] > items[j+1]: 
                items[j], items[j+1] = items[j+1], items[j]

```

#### With line numbers 

```py linenums="1"

def bubble_sort(items): 
    for i in range(len(items)): 
        for j in range(len(items) - 1 - i):
            if items[j] > items[j+1]: 
                items[j], items[j+1] = items[j+1], items[j]

```


#### With line highlighted code lines 

```py hl_lines="2 4" linenums="1"

def bubble_sort(items): 
    for i in range(len(items)): 
        for j in range(len(items) - 1 - i):
            if items[j] > items[j+1]: 
                items[j], items[j+1] = items[j+1], items[j]

```
-- ### Plain code block

## Icons and Emojis

:smile:

:fontawesome-regular-face-laugh-wink:

:fontawesome-brands-twitter:{ .twitter }

:octicons-heart-fill-24:{ .heart }
