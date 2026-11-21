# El diario de Pao

Una página estática para crear un periódico infantil con el pronóstico meteorológico de hoy y dos pasatiempos diarios: una sopa de letras y un sudoku 6×6 para principiantes. Pensado para niñas y niños de hasta 10 años. Elige una ciudad o comparte la ubicación del navegador, resuelve los juegos en pantalla o pulsa **Crear mi periódico en PDF** para imprimirlos. En la ventana de impresión selecciona **Guardar como PDF**.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub y sube `index.html` y `README.md`.
2. En el repositorio, abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**, elige `main` y la carpeta `/ (root)`, y guarda.
4. GitHub publicará la página en `https://<usuario>.github.io/<repositorio>/`.

No necesita compilación ni dependencias. El pronóstico y la búsqueda de ciudades usan las API públicas de [Open-Meteo](https://open-meteo.com/). El botón de PDF usa la función de impresión del navegador.
