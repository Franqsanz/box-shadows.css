[![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

# CSS Box Shadows

![header](./img/header.png)

Mini librería `CSS` de sombras que puedes utilizar en tus proyectos.

### Instalación
Visita el sitio para descargar: [https://cssshadows.netlify.app/](https://cssshadows.netlify.app/)

### Modo de uso

La forma de utilizar esta librería es como cualquier archivo `CSS`. Solo debes enlazarlo en el `<head>`.

Ejemplo:

```HTML
<head>
  <link rel="stylesheet" href="./shadows.min.css">
</head>
```

**❗ ATENCIÓN ❗**

> Solo hay **clases** en está librería, no puedes usar `id`.

Entonces debes llamar los `class` desde las etiquetas que utilizes.
Por ejemplo un `<div>`.

### Color de la sombra
- `#CACACA`
- `rgb(202, 202, 202)`
- `hsl(0, 0%, 79%)`

### Tipos de clases disponibles

- Clases con efecto `Blur`.
- Clases con efecto `Solid`.
- Clases con efecto `Multi Colors`.

### Descripción de las letras:
Estás letras hacen referencia a la posición de la sombra. Las verás en las clases que están más abajo.

| Letra | Descrición |
| ----- | ---------- |
| C     | Center     |
| L     | Left       |
| R     | Right      |
| T     | Top        |
| B     | Botton     |

En las sombras multi colores poseen dos posiciones, por ejemplo: `left-top`, osea posicionada arriba a la izquierda.


#### Clases efecto `Blur`

Los números que contienen las clases hacen referencia a la cantidad de píxeles de `blur`.

Ejemplo:

```HTML
<div class="sw-b-30-b"></div>

<!--
  Está clase contiene una sombra tipo blur de 30px posicionada en la línea inferior del elemento,
  el nombre completo sería así: "shadows-blur-30-botton".
-->
```

![sample1](./img/botton-30.png)

| Clases      |
| ----------- |
| `sw-b-10-c` |
| `sw-b-10-l` |
| `sw-b-10-r` |
| `sw-b-10-t` |
| `sw-b-10-b` |
| `sw-b-20-c` |
| `sw-b-20-l` |
| `sw-b-20-r` |
| `sw-b-20-t` |
| `sw-b-20-b` |
| `sw-b-30-t` |
| `sw-b-30-l` |
| `sw-b-30-b` |
| `sw-b-30-r` |
| `sw-b-30-c` |
| `sw-b-40-c` |
| `sw-b-40-t` |
| `sw-b-40-l` |
| `sw-b-40-r` |
| `sw-b-40-b` |
| `sw-b-50-c` |
| `sw-b-50-t` |
| `sw-b-50-l` |
| `sw-b-50-r` |
| `sw-b-50-b` |

#### Clases efecto `Solid`

Los números que contienen las clases hacen referencia a la cantidad de píxeles de `Solid`.

Ejemplo:

```HTML
<div class="sw-s-10-r"></div>
```

![sample2](./img/solid.png)

| Clases      |
| ----------- |
| `sw-s-10-c` |
| `sw-s-10-l` |
| `sw-s-10-r` |
| `sw-s-10-t` |
| `sw-s-10-b` |
| `sw-s-20-c` |
| `sw-s-20-l` |
| `sw-s-20-r` |
| `sw-s-20-t` |
| `sw-s-20-b` |

#### Clases efecto `Multi Colors`

Estás clases contienen varias capas de sombras multi colores _(Experimental)_.

Ejemplo:

```HTML
<div class="sw-s-mlt-clr-l-b"></div>
```

![sample2](./img/multi-colors.png)

| Clases             |
| ------------------ |
| `sw-s-mlt-clr-r-t` |
| `sw-s-mlt-clr-l-t` |
| `sw-s-mlt-clr-r-b` |
| `sw-s-mlt-clr-l-b` |
| `sw-s-mlt-clr-t`   |
| `sw-s-mlt-clr-b`   |

---

### Licencia

[MIT](LICENSE)
