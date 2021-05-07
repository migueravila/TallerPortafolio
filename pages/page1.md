<div align="center">
    <h1>Maquetando con HTML</h1>
</div>

### 📐 La estructura básica html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portafolio</title>
  </head>
  <body></body>
</html>
```

### 🪧 La estructura de nuestra tarjeta

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portafolio</title>
  </head>
  <body>
    <div class="card">
      <div class="container">
        <div class="photo">
          <img src="img/photo.jpg" alt="photo" />
        </div>
        <h1 class="greeting accent"></h1>
        <p class="text"></p>
        <h4 class="subtitle accent"></h4>
        <p class="text"></p>
        <h4 class="subtitle accent"></h4>
        <p class="text"></p>
        <div class="footer"></div>
      </div>
    </div>
  </body>
</html>
```

### ℹ️ Coloquemos información!

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portafolio</title>
  </head>
  <body>
    <div class="card">
      <div class="container">
        <div class="photo">
          <img src="img/photo.jpg" alt="photo" />
        </div>
        <h1 class="greeting accent">
          👋 ¡Hola! Soy John, estudiante de preparatoria y amo la tecnología.
        </h1>
        <p class="text">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi dapibus
          lectus libero, in varius erat consequat vel. Nunc faucibus dolor eu
          tellus tempus congue. Morbi mollis sagittis pulvinar. Curabitur
          varius, dolor vitae elementum tristique, justo turpis interdum lorem,
          vitae congue eros sapien at felis. Cras fermentum nibh rhoncus
          pulvinar aliquet. Curabitur vel purus eget lacus luctus maximus ac et
          eros. Etiam mattis nisi in pellentesque ultrices. Donec vel nibh non
          turpis tempus iaculis. Nullam eget ornare ante, non tempor eros. Ut
          eget nibh eget orci sollicitudin dictum sed id mi. Fusce ut eleifend
          nulla, id maximus arcu. Vivamus scelerisque dapibus lectus sit amet
          sodales.
        </p>
        <p class="text">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi dapibus
          lectus libero, in varius erat consequat vel. Nunc faucibus dolor eu
          tellus tempus congue. Morbi mollis sagittis pulvinar. Lorem ipsum
          dolor sit amet, consectetur adipiscing elit. Morbi dapibus lectus
          libero, in varius erat consequat vel. Nunc faucibus dolor eu tellus
          tempus congue. Morbi mollis sagittis pulvinar.
        </p>
        <h4 class="subtitle accent">🎨 Mis habilidades</h4>
        <p class="text">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi dapibus
          lectus libero, in varius erat consequat vel. Nunc faucibus dolor eu
          tellus tempus congue. Morbi mollis sagittis pulvinar. Lorem ipsum
          dolor sit amet, consectetur adipiscing elit. Morbi dapibus lectus
          libero, in varius erat consequat vel. Nunc faucibus dolor eu tellus
          tempus congue. Morbi mollis sagittis pulvinar
        </p>
        <h4 class="subtitle accent">🚀 Mis proyectos</h4>
        <p class="text">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi dapibus
          lectus libero, in varius erat consequat vel. Nunc faucibus dolor eu
          tellus tempus congue. Morbi mollis sagittis pulvinar. Lorem ipsum
          dolor sit amet, consectetur adipiscing elit. Morbi dapibus lectus
          libero, in varius erat consequat vel. Nunc faucibus dolor eu tellus
          tempus congue. Morbi mollis sagittis pulvinar
        </p>
        <div class="footer">
          Puedes enviarme un correo a migueravila@pm.me, puedes encontrarme como
          migueravila en Github.
        </div>
      </div>
    </div>
  </body>
</html>
```

## [Anterior 👈](../README.md) - [👉 Siguiente](page2.md)
