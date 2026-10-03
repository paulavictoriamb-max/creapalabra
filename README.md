# Ojochat

Te damos dos letras. Escribe una palabra que empiece con una y termine con la otra antes de que se cierren los ojos.

## Cómo jugar

1. Abre `index.html` en el navegador.
2. Escribe tu nombre, elige cuántos jugadores y cuántas rondas, y pulsa **Crear sala**.
3. Comparte el enlace de invitación (vence en 10 minutos).
4. En cada ronda aparecen dos letras: escribe una palabra que empiece con una y termine con la otra (o al revés) antes de que pasen los 10 segundos.
5. Ganas 10 puntos por palabra válida, más puntos extra si respondes rápido.

Al final se muestran las posiciones y los premios al **más rápido** y a la **palabra más larga**.

## Notas técnicas

- Todo el juego está en un solo archivo: `index.html` (HTML, CSS y JavaScript sin dependencias).
- Incluye un diccionario de español de unas 365 mil palabras, comprimido con gzip dentro de la página.
- El multijugador usa `BroadcastChannel`, así que por ahora solo funciona entre pestañas del mismo navegador. El siguiente paso es cambiarlo por Supabase Realtime para jugar desde distintos dispositivos.
