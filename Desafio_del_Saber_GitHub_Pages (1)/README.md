# Desafío del Saber — Catamarca Aprende +

Juego de preguntas para jóvenes, listo para GitHub Pages. Incluye cuatro áreas temáticas (Matemática, Lengua, Ciencias y Mundo digital), 10 preguntas aleatorias por partida, cronómetro opcional, puntaje, pistas, comodín 50/50, revisión de respuestas y sonido opcional.

## Publicación en GitHub Pages

1. Crear un repositorio nuevo en GitHub, por ejemplo `desafio-del-saber`.
2. Subir el archivo `index.html` a la **raíz** del repositorio (el ZIP sirve para descargar y descomprimir primero).
3. Ir a **Settings → Pages** y seleccionar **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
4. Guardar y esperar a que GitHub muestre la URL pública.

No requiere instalación, cuentas, claves ni servidor. Todas las preguntas y la lógica están dentro de `index.html`. El juego funciona sin conexión; la tipografía usa una fuente web opcional y tiene alternativa local.

**Nota de identidad visual:** el encabezado usa el nombre textual Catamarca Aprende +. No incluye un escudo ni logo institucional oficial, porque no fue suministrado para esta entrega.

## Personalización

Las preguntas se encuentran en el objeto `data` dentro de `index.html`. Cada pregunta incluye en orden: consigna, cuatro opciones, índice de respuesta correcta (0 a 3), pista y explicación.
