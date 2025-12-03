Pon aquí tus imágenes para que `catalogo.html` las use automáticamente.

Reglas de uso:

- Coloca archivos de imagen (png, jpg, jpeg, svg, gif) dentro de esta carpeta `images/`.
- El script automático intentará usar el nombre derivado del atributo `alt` de cada <img> (sanitizado).
  - Ejemplo: Si una imagen tiene `alt="Pokemon ETB Zenit Supremo"`, el script buscará `images/pokemon_etb_zenit_supremo.png` (o con otra extensión si la original la tenía).
- Si quieres forzar un nombre concreto, añade `data-local="miarchivo.png"` en la etiqueta <img> correspondiente.
  - Ejemplo: <img src="https://..." alt="..." data-local="zenit_supremo.png">

Notas:
- Live Server servirá estas imágenes si colocas la carpeta `images/` en el mismo nivel que `catalogo.html`.
- Si no pones imágenes locales, la página seguirá mostrando las imágenes remotas originales.
