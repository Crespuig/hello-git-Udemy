# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabercera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- formato *italica* de la primera forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primera forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal.
- Aqui podemos usar *formato italico*, pero también **bold** y ~~tachado~~.

# Listas
1. Esto es un  item de lista ordenada.
2. Esto es un  item de lista ordenada.
3. Esto es un  item de lista ordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo GitHub](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSYahwTogTCxlS6qj1Ccwzdgsyd0PvWpqg3hg&usqp=CAU)

# Code Snippets
Codigo en JSON
```JSON
[
    {
        "title": "apples",
        "count": [12000, 20000],
        "description": {"text": "...", "sensitive": false}
    },
    {
        "title": "oranges",
        "count": [17500, null],
        "description": {"text": "...", "sensitive": false}
    }
]
```
Codigo en Javascript
```Javascript
function getAction()
    {
            var x=document.forms.myForm;
            alert(x.action);
    }
    
    function changeAction(action)
    {
            var x=document.forms.myForm;
            x.action=action;
            alert(x.action);
    }
```