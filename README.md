# claude-skills-starter

Colección de skills para Claude: estudio, flashcards, páginas de aprendizaje, productividad y creación de animaciones 2D. Incluye guías de instalación en español.

## Skills de animación 2D

Están en `.claude/skills/`. Cada skill se puede invocar por su nombre en Claude Code:

- `/animation-brief`: convertir una idea en un plan de producción claro.
- `/storyboard-animatic`: diseñar escenas, planos, poses clave y ritmo.
- `/character-design-2d`: crear personajes consistentes y hojas de modelo.
- `/animate-2d`: planear y producir la animación con principios sólidos.
- `/sprite-sheet`: preparar spritesheets y metadatos para juegos o web.
- `/animation-qa-export`: revisar, exportar y organizar los entregables.

### Instalación

Para usar estas skills en un proyecto con Claude Code, copia la carpeta `.claude/skills/` a la raíz del proyecto. También puedes copiar solo las skills que necesites. Claude detectará cada `SKILL.md` y podrás invocarlo con `/nombre-de-la-skill`.

### Flujo sugerido

1. Define la idea y los requisitos con `/animation-brief`.
2. Prepara la secuencia con `/storyboard-animatic` y los diseños con `/character-design-2d`.
3. Produce el movimiento con `/animate-2d`.
4. Si el destino es un juego, organiza los cuadros con `/sprite-sheet`.
5. Pasa el control final y los formatos de salida por `/animation-qa-export`.

Las instrucciones son independientes de una herramienta concreta: Claude debe confirmar el formato, el motor o software de destino y las limitaciones antes de generar archivos, y no debe afirmar que exportó o renderizó algo que no haya podido comprobar.