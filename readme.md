# CSS Box Shadows

![header](./img/header.png)

Mini librería `CSS` de sombras que puedes utilizar en tus proyectos.

### Instalación
[Descargar](https://cssshadows.netlify.app/lib/shadows.min.css) archivo comprimido.
[Descargar](https://cssshadows.netlify.app/lib/shadows.css) archivo descomprimido.

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

#### Clases efecto `Blur`

Los números que contienen las clases hacen referencia a la cantidad de píxeles de `blur`.

Ejemplo:

```HTML
<div class="sw-blur-30-botton"></div>
```

![sample1](./img/botton-30.png)

| Clases                  |
| ----------------------- |
| `sw-blur-10-center` |
| `sw-blur-10-left`   |
| `sw-blur-10-right`  |
| `sw-blur-10-top`    |
| `sw-blur-10-botton` |
| `sw-blur-20-center` |
| `sw-blur-20-left`   |
| `sw-blur-20-right`  |
| `sw-blur-20-top`    |
| `sw-blur-20-botton` |
| `sw-blur-30-top`    |
| `sw-blur-30-left`   |
| `sw-blur-30-botton` |
| `sw-blur-30-right`  |
| `sw-blur-30-center` |
| `sw-blur-40-center` |
| `sw-blur-40-top`    |
| `sw-blur-40-left`   |
| `sw-blur-40-right`  |
| `sw-blur-40-botton` |
| `sw-blur-50-center` |
| `sw-blur-50-top`    |
| `sw-blur-50-left`   |
| `sw-blur-50-right`  |
| `sw-blur-50-botton` |

#### Clases efecto `Solid`

Los números que contienen las clases hacen referencia a la cantidad de píxeles de `Solid`.

Ejemplo:

```HTML
<div class="sw-solid-10-right"></div>
```

![sample2](./img/solid.png)

| Clases                   |
| ------------------------ |
| `sw-solid-10-center` |
| `sw-solid-10-left`   |
| `sw-solid-10-right`  |
| `sw-solid-10-top`    |
| `sw-solid-10-botton` |
| `sw-solid-20-center` |
| `sw-solid-20-left`   |
| `sw-solid-20-right`  |
| `sw-solid-20-top`    |
| `sw-solid-20-botton` |

#### Clases efecto `Multi Colors`

Estás clases contienen varias capas de sombras multi colores _(Experimental)_.

Ejemplo:

```HTML
<div class="sw-solid-mlt-clr-left-botton"></div>
```

![sample2](./img/multi-colors.png)

| Clases                                   |
| ---------------------------------------- |
| `sw-solid-mlt-clr-right-top`    |
| `sw-solid-mlt-clr-left-top`     |
| `sw-solid-mlt-clr-right-botton` |
| `sw-solid-mlt-clr-left-botton`  |
| `sw-solid-mlt-clr-top`          |
| `sw-solid-mlt-clr-botton`       |

---

### Licencia

[MIT](LICENSE)
