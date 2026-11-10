---
name: animation-qa-export
description: Revisa una animación 2D y prepara una lista de exportación y organización de archivos según su destino. Úsala antes de entregar, publicar o integrar la animación.
---

# Revisión y exportación de animación 2D

Haz una revisión final visual y técnica, y prepara entregables reproducibles según el destino solicitado.

## Revisión visual

- La acción y emoción se entienden a velocidad real.
- Personajes, proporciones, colores y continuidad respetan el diseño aprobado.
- No hay cuadros perdidos, saltos, parpadeos, líneas temblorosas ni artefactos involuntarios.
- Los contactos, arcos y transiciones se sienten intencionales.
- El loop cierra sin salto perceptible, cuando corresponda.

## Revisión técnica

- Confirma dimensiones, fps, duración, orientación, transparencia, perfil de color y formato.
- Comprueba que audio, subtítulos o texto cumplan los requisitos del destino, si existen.
- Verifica tamaño, nombres, rutas y estructura de archivos. Para spritesheets, valida también cuadros, atlas y metadatos.
- Comprueba legibilidad en el tamaño final y compatibilidad con el reproductor o motor de destino.

## Entrega

Propón una carpeta clara, por ejemplo `source/`, `exports/` y `preview/`, adaptándola al proyecto existente y sin mover ni sobrescribir archivos sin permiso. Lista los formatos y parámetros de exportación; distingue archivos realmente creados de instrucciones pendientes. Si no puedes renderizar o validar el archivo, dilo explícitamente y ofrece pasos de comprobación apropiados para la herramienta de destino.