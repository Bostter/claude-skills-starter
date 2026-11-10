---
name: sprite-sheet
description: Planifica y organiza spritesheets para juegos o web, con cuadros, pivotes, atlas y metadatos. Úsala cuando la animación deba convertirse en sprites individuales o una hoja de sprites.
---

# Spritesheets y atlas

Prepara una especificación de spritesheet que sea fácil de consumir por el motor o aplicación de destino.

## Proceso

1. Confirma motor/destino, tamaño de cuadro, número de animaciones, orientación, transparencia, margen, espaciado, padding y formato de metadatos. Si falta información, declara supuestos o pregunta.
2. Define una convención de nombres estable para animaciones y cuadros, por ejemplo `idle_000`, `run_001`; evita caracteres que compliquen el uso en herramientas.
3. Mantén dimensiones y alineación consistentes. Define origen/pivote por personaje y anota excepciones intencionales.
4. Elige orden del atlas y estrategia de empaquetado compatible con el destino. Considera límites de textura, filtrado, padding y sangrado de color para evitar artefactos en bordes.
5. Entrega la lista de cuadros y los metadatos que solicite el usuario (por ejemplo, JSON), indicando unidades, coordenadas y si son relativas o absolutas.
6. Comprueba que el número de cuadros, nombres, dimensiones y rangos de animación concuerden. No inventes coordenadas finales si todavía no se ha creado o medido la imagen del atlas.

## Entrega

Incluye especificación del atlas, tabla de animaciones (nombre, cuadros, fps, loop y pivote) y formato de metadatos. Si el destino tiene requisitos propios, sigue esos requisitos y señala incompatibilidades antes de producir recursos.