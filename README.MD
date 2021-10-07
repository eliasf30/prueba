
# cabeceras

# cabecera h1


## cabecera h2

### cabecera h3

#### cabecera h4

##### cabecera h5

###### cabecera h6

# underlines

underline 1
-----------

underline 2
===========

# formatos de enfasis

- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.

- formato **bold** o **strong**
- formato __bold__ o __strong__

formato ~~tachado~~.

aqui podemos usar formato *italico*, pero tambien **bold** y ~~tachado~~

# listas 

1. esto es un item de lista ordenada
2. esto es un item de lista ordenada
3. esto es un item de lista ordenada

- esto es un item de lista desordenada
- esto es un item de lista desordenada
- esto es un item de lista desordenada

# links

<a href="http://www.google.com">esto es un link html</a>

[esto es un link en markdown](http://google.com)

[esto es un link al index](index.html)

# imagenes
![logo github](https://cdn-icons-png.flaticon.com/512/25/25231.png)

# code snippets

codigo en JSON
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
codigo en javascript
```javascript
JavaScript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;

```

# tablas

| nombre | apellido | documento |
| ------|------------| ----------|
|maxi | burgos | 2343242343 | 
| tomas | thompson | 232321321 |

# citas
esto es un texto referente a una cita que pondremos debajo 
> esto es una cita.

esto es otro texto que no se relaciona con la cita anterior
> esto es otra cita

# lineas divisoras
esto es un texto que sera dividido por giones medios

---
esto es otro texto dividido por asteriscos.

***

esto es otro texto dividido por guiones bajos

___

# saltos de linea
esto es nuestro primer parrafo.

esto es nuestro segundo parrafo.

esto es nuestro tercer parrafo.
