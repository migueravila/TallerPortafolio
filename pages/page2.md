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

### 📏 Variables de

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
  --primary: #4568dc;
  --secondary: #b06ab3;
}
```

### 🤲 Reset CSS

### 📱 Background y gradientes

### 🪧 Una tarjeta bonita

### 📦 Un contenedor de texto

### 👤 Nuestra foto de perfil

### 📖 Titulos y textos

### 🐙 Breve introducción a animaciones

### 🔗 Reset de links

### 📱 Breve vistazo a responsive design

## [Anterior 👈](page1.md) - [👉 Siguiente](page3.md)
