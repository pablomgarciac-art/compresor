# Compresor de fotos

Herramienta web para reducir el peso de muchas fotos de una vez, sin subirlas a ningún servidor: todo se procesa en el navegador.

## Qué hace

- Suelta varias fotos o una carpeta entera (la estructura de carpetas se conserva en el ZIP).
- Elige el formato de salida: original, JPEG, WebP o PNG.
- Elige la calidad: Ligera (por defecto), Equilibrada o Casi sin pérdida.
- Elige la resolución: original, lado más largo de 2560 a 800 px (1920 por defecto) o porcentaje (80, 60 o 50 %). Nunca amplía una foto pequeña.
- Con una carpeta, descarga todo en un ZIP con el nombre de la carpeta.
- Portada ligera para elegir fotos o carpeta. Una vez cargadas, hay botones para añadir más.
- Los ajustes (formato, calidad, resolución y nombre) están en el panel **Ajustes**, arriba a la derecha.
- **Nombre**: por defecto cada foto conserva su nombre. Puedes añadir un texto al final (por ejemplo `-optimizada`) para distinguir las ya comprimidas.
- Muestra el peso antes y después de cada foto y el ahorro total.
- Comparador antes/después con divisor y vista 1:1 para comprobar la calidad.
- Descarga cada foto por separado o todas en un ZIP.
- Elimina los metadatos de las fotos, incluida la ubicación GPS.

## Uso

Abre `index.html` en el navegador. No necesita instalación ni dependencias.

Para publicarlo como página web con GitHub Pages: en el repositorio, **Settings → Pages**, elige la rama `main` y la carpeta `/ (root)`.

## Instalar en el móvil

Con la página publicada (GitHub Pages), ábrela en el móvil y usa **Añadir a pantalla de inicio** (Safari) o **Instalar app** (Chrome). Se instala con el icono amarillo de la foto y se abre a pantalla completa. Los iconos están en `icon.svg`, `icon-192.png`, `icon-512.png` y `apple-touch-icon.png`.

## Límites

- Los archivos HEIC (iPhone) no se pueden leer en la mayoría de navegadores.
- Los GIF animados se convierten en imagen fija.
- Elegir una carpeta con el botón no funciona en la mayoría de móviles; arrastrarla en ordenador sí.
- La compresión sin pérdida real solo existe en PNG. En JPEG y WebP, entre 80 y 90 de calidad la diferencia suele pasar desapercibida.
