# Kiokugiri — sitio web HTML y CSS

Proyecto listo para abrir en Visual Studio Code. No requiere instalación de paquetes, servidor, conexión a internet ni JavaScript.

## Archivos

- `index.html`: página principal, inspirada en la primera imagen de referencia. Contiene la portada de Kiokugiri, deja vacía la descripción y ofrece **un único enlace** al Capítulo 1.
- `capitulo1.html`: lector vertical del capítulo, con las **seis imágenes** proporcionadas en el orden original.
- `styles.css`: estilos de ambas páginas y adaptaciones para pantallas pequeñas.
- `assets/portada.png`: segunda imagen proporcionada.
- `assets/pagina-01.png` a `assets/pagina-06.png`: imágenes restantes del capítulo, en orden.

## Cómo abrirlo en VS Code

1. Descomprime la carpeta `kiokugiri-web`.
2. Abre Visual Studio Code y selecciona **Archivo > Abrir carpeta**.
3. Selecciona la carpeta `kiokugiri-web`.
4. Abre `index.html` en un navegador (doble clic) o usa la extensión **Live Server** y la opción **Open with Live Server**.
5. Haz clic en **Capítulo 1: El vacío** para acceder al lector vertical.

### Dónde editar el contenido

- Para escribir la descripción después, busca `<!-- La descripción queda intencionalmente vacía. -->` en `index.html` y añade el texto en el `<div class="description-space">`.
- Para editar colores, cambia las variables dentro de `:root` en `styles.css`.
- Para cambiar imágenes, reemplaza los archivos en `assets/` por otros del mismo nombre.

> El buscador, los textos del menú y el inicio de sesión son decorativos y no incluyen funciones ni enlaces, tal como se solicitó: solo existe un enlace al capítulo desde la ficha.
