# Conecta 3 por puntos

Juego para el laboratorio de búsqueda adversaria del curso de Inteligencia Artificial.

**Jugar:** https://ferdiex.github.io/conecta3/

## Reglas

- Elige una columna; tu ficha cae hasta la casilla libre más baja.
- Cada tres fichas tuyas en línea (horizontal, vertical o diagonal) valen un punto.
- Cuando se llena el tablero (6 filas × 5 columnas), gana quien tenga más puntos.

## El agente

Juega con minimax y poda alfa-beta, con profundidad de corte ajustable (1 a 7) y dos funciones de evaluación: una ingenua (solo cuenta puntos) y una buena (también cuenta líneas que aún pueden completarse).

Con juego perfecto el juego termina en empate.

## Uso local

Es un solo archivo, `index.html`: basta con abrirlo en cualquier navegador.

Fernando Montes-Gonzalez · Universidad Veracruzana
