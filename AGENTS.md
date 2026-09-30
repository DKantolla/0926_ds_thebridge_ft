# AGENTS.md

## Alcance

Este directorio contiene material docente de un bootcamp de Data Science de TheBridge. El contenido principal está en `1-Fundamentals/`, con notebooks de Markdown, Python básico, flujos de control, colecciones, funciones y orientación a objetos.

## Forma de trabajar

- Responde en español salvo que el usuario pida otro idioma.
- No muestres al usuario listas de cosas que debe hacer en el código ni instrucciones paso a paso de implementación. Ejecuta los cambios solicitados y comunica únicamente el resultado, los archivos afectados y las comprobaciones realizadas.
- Mantén el propósito didáctico de los materiales: no conviertas ejercicios, plantillas vacías o bloques `TODO` en soluciones completas salvo petición explícita.
- Distingue entre este árbol (`MIREPO/Untitled`) y la copia hermana `0926_ds_thebridge_ft`; confirma siempre el árbol objetivo antes de editar.
- Conserva nombres, acentos, estructura de carpetas y salidas de notebooks salvo que el cambio solicitado requiera modificarlos.

## Notebooks y Python

- Trata los `.ipynb` como documentos con celdas Markdown, Python y ocasionalmente `raw`; cambia solo las celdas necesarias.
- No tomes los outputs guardados como prueba del estado actual. Cuando sea relevante, valida la celda o el script en el kernel disponible.
- Algunos ejercicios usan `input()` y requieren ejecución interactiva; no los ejecutes automáticamente de forma que puedan quedar bloqueados.
- Respeta la diferencia entre archivos de ejercicios, archivos de clase vacíos y soluciones (`Extra/`, `solutiones.py`).
- Evita introducir dependencias nuevas: el proyecto no declara `requirements.txt`, `pyproject.toml` ni una suite de tests.

## Validación

- Para scripts Python, usa una comprobación sintáctica o ejecución directa del archivo cuando sea segura.
- Para notebooks, selecciona un kernel compatible en VS Code y valida solo las celdas afectadas; documenta los errores de ejecución que ya existían.
- No inventes comandos de build o test que el repositorio no define.

## Documentación

- Consulta la [guía de Git](1-Fundamentals/Git/Intro_git.md) para el contexto formativo existente.
- Mantén la documentación específica en sus archivos actuales; enlázala en lugar de duplicarla.
