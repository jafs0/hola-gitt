# Cabeceras 

# cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
###### Cabecera H5
###### Cabecera H6

# Underlines

Underline 1
-----------
underline 2
===========

# Enfasis

- formato letra *italica* de la primer forma. 
- formato letra _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~.
- aqui podemos usar *formato italico*, pero tambien **bold** y ~~tachado~~.

# Listas

1. esto es un items de lista ordenadas.
2. esto es un items de lista odernadas.
3. esto es un items de lista ordenadas.

- esto es un items de lista desordenadas.
- esto es un items de lista desordenadas.
- esto es un items de lista desordenadas.

# links

- <a href="http//www.google.com">Esto es un links en html</a>
- [Esto es un link en markdown](http//www.google.com)
- [Esto es un link al index](index.html)

# Imagenes.

![logo de github](https://image.flaticon.com/icons/png/512/38/38401.png)

# Code snippets.
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

```JSON
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
# Tablas.

| Nombre | Apellido | Documento |
|------- |--------- |---------- |
| Juan   | Florian  | 406263883 |
| Carlos | Coiscou  | 402040403 |

# Citas

Esto es un texto referente a una cita:

> Esto es una cita.

> esto es otra cita.

# Lineas divisoras

Esto es un texto que sera dividido por guines medios.

---
Esto es un texto que sera dividido por asteriscos.

***
Esto es un texto que sera dividido por rayita bajas.

___

# Saltos de lineas
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- lista