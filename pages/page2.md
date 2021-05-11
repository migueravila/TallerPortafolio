<div align="center">
    <h1>Diseñando con CSS</h1>
</div>

### 🧶 Las fuentes

Cuando hablamos de diseño web y de estilizar una página, uno de los primeros cambios que queremos hacer en el momento en el que vemos nuestra es sin duda cambiar la fuente.

El texto es una pieza fundamental del diseño de una página web y hay una herramienta fántastica llamada [Google Fonts](https://fonts.google.com/) que nos ayuda a encontrar fuentes geniales para nuestros sitios web. En este caso usaremos `Open Sans`. Una fuente genial para interfaces. Y la agregaremos de la siguiente forma como el primer elemento de nuestro código css:

```css
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap');

body {
  font-family: 'Open Sans', sans-serif;
}
```

### 📏 Variables de CSS

Uno de los conceptos más increibles que han introducido últimamente a CSS son las variables. Son pedacitos de información que podemos guardar con cierto nombre para poder invocarlo nuevamente más abajo y de esa forma no repetirnos muchas veces. Estas se usan declarando la siguiente estructura:

```css
:root {
  --nombreDeLaVariable: Valor de la variable;
}
```

Y nosotros las aprovecharemos para almacenar los valores de nuestros colores:

```css
:root {
  --bg: #2d2a32;
  --fg: #ffeddf;
  --buttonbg: #ffeddf;
  --primary: #ac46b0;
  --secondary: #b06ab3;
}
```

Y las podemos llamar en cualquier parte de nuestro código css de la siguiente manera:

```css
body {
  color: var(--fg);
}
```

### 🤲 Reset CSS

El `reset` de CSS es una de las práctica más usadas desde hace mucho tiempo para usar CSS de manera profesional. Todos los navegadores brindan una capa de estilos predeterminada por lo que debemos deshacernos de ella para tener el control total del diseño (Y hacer que nuestra página se vea igual en todos los navegadores):

```css
*,
*::after,
*::before {
  margin: 0;
  padding: 0;
  box-sizing: inherit;
}
```

### 📱 Background y gradientes

Muchas personas prefieren usar fondos blancos o negros. Pero debido al diseño que queremos buscar usaremos una propiedad muy genial de CSS llamada `linear-gradient` (pueden leer más sobre ella en [MDN](<https://developer.mozilla.org/en-US/docs/Web/CSS/linear-gradient()>). La cual nos permite crear un efecto increible de gradiente.

Para usarla necesitamos la siguiente estructura:

```css
selector {
  background: linear-gradient(direccion, color1, color2);
}
```

Y debido a que queremos colocarla en toda nuestra página, usaremos el selector **body** y usaremos los colores que declaramos anteriormente en las variables

```css
body {
  background: linear-gradient(to right, var(--secondary), var(--primary));
}
```

### 🪧 Una tarjeta bonita

Aqui usaremos nuestra clase `card` y lo primero que debemos hacer es otorgarle un color de fondo y añadiremos una nueva propiedad a nuestro repertorio, el `box-shadow`. El cual funciona de la siguiente manera:

```css
selector {
  box-shadow: posicionX posicionY BlurRadius Color;
}
```

Donde la **posicionX** representa su posición en X con respecto al objeto, la **posicionY** lo mismo pero en el eje Y y el **BlurRadius** el nivel de difuminado de el **color** elegido. Y nosotros lo usaremos de la siguiente forma:

```css
.card {
  background-color: var(--bg);
  box-shadow: 10px 20px 20px rgba(0, 0, 0, 0.35);
}
```

Ahora ocuparemos las propiedades de `margin` y `padding` de la siguiente forma:

```css
.card {
  margin: 2vh auto;
  padding: 30px;
  width: 94vw;
}
```

Esto nos dará como resultado que nuestra tarjeta se posicione **2**% abajo de la altura de nuestra pantalla y se centrará **automaticamente** en el ancho. El padding nos dará aún más espacio para que se vea mejor en los contornos. Y finalmente la propiedad `width` nos mostrará la tarjeta con un ancho total al 94% de nuestra pantalla.

Ya por último usaremos una nueva propiedad muy cool para el diseño, el `border-radius` el cual nos permite redondear las esquinas del elemento que seleccionemos:

```css
.card {
  border-radius: 5px;
}
```

Por lo que al final nuestro código será:

```css
.card {
  background-color: var(--bg);
  box-shadow: 10px 20px 20px rgba(0, 0, 0, 0.35);

  margin: 2vh auto;
  padding: 30px;
  width: 94vw;

  border-radius: 5px;
}
```

### 📦 Un contenedor de texto

### 👤 Nuestra foto de perfil

### 📖 Titulos y textos

### 🐙 Breve introducción a animaciones

### 🔗 Reset de links

### 📱 Breve vistazo a responsive design

Para que nuestras páginas logren verse en todos los dis

## [Anterior 👈](page1.md) - [👉 Siguiente](page3.md)
