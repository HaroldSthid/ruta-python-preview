# Ruta Python — Mockup de referencia

Propuesta visual para hacer la [Hoja de Ruta Python — Colombia](https://ivangomezgb.github.io/HOJA_RUTA_PYTHON_COLOMBIA/)
más accesible para personas sin experiencia técnica, manteniendo la profundidad que ya tiene
para quien sigue el track completo — y heredando la identidad visual real de
[python.org.co](https://python.org.co/), porque esta ruta va a estar vinculada al sitio oficial.

Este repo **no reemplaza** el sitio actual ni su contenido pedagógico, ni bifurca la experiencia
en dos productos separados. Es una sola ruta con un solo punto de llegada — el selector de
audiencia elige en qué escalón arrancás, no a qué sitio vas. Es un recurso paralelo para alinear
dirección visual antes de tocar el código real, en línea con el trabajo que vienen impulsando
**Leo y Angel** en el proyecto.

## Recursos

- **[Ver el mockup](https://haroldsthid.github.io/ruta-python-preview/)** — vista Desktop y Mobile, estático
- **[Canvas interactivo](https://claude.ai/artifact/CW7k7L5cccoYE6iyEEtvGc)** — versión editable (Claude Design)
- **[Guía para el Front-end Developer](https://haroldsthid.github.io/ruta-python-preview/guide.html)** — mapeo concreto de qué cambia en `styles.css` / `index.html` del repo original

## Qué es esto

Un HTML/CSS vanilla (sin build step, igual que el sitio original) que muestra cómo se vería
la ruta con:

- Paleta, tipografía (Titillium Web) y franja de colores heredadas de python.org.co — no inventadas
- Hero con selector de punto de partida ("Nunca programé antes" / "Ya tengo bases"), misma ruta para los dos
- Playground destacado cerca del hero, no al final
- Tarjetas de fase con ícono y badge de estado
- Checklist con progreso visual por bloques, en vez de un contador plano

## Correr localmente

Sin dependencias ni build step — abrir `index.html` directo en el navegador, o:

```bash
python -m http.server 8000
```

## Créditos

Contenido y estructura pedagógica: **Leo y Angel**, impulsores de la Hoja de Ruta Python — Colombia.
Esta propuesta visual no cambia ni reemplaza ese trabajo, solo sugiere una forma de presentarlo.
