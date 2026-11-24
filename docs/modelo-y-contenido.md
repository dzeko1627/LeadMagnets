# Modelo y contenido del orientador

## Objetivo

Ayudar a futuros alumnos a explorar posibles direcciones profesionales en IA/Tech según sus objetivos, experiencia y preferencias de aprendizaje. Al final se sugiere una ruta formativa como posible siguiente paso. La evaluación tiene 12 preguntas y está pensada para completarse en unos 5–10 minutos.

## Cuestionario

1. **Nivel de estudios actual** — ESO, Bachillerato/FP medio, FP superior, grado, posgrado o prefiere no indicarlo. Se recoge como contexto y no influye en la recomendación.
2. **Objetivo a un año** — respuesta abierta sobre el cambio que la persona quiere conseguir.
3. **Caso real** — respuesta abierta sobre una tarea, dificultad o idea que quiere abordar.
4. **Contexto de aplicación** — trabajo actual, proyecto digital/tecnológico, cambio profesional o exploración.
5. **Primer resultado esperado** — reducir tareas manuales, decidir con datos, crear un producto digital o conectar herramientas.
6. **Experiencia práctica** — selección múltiple de automatización, análisis de datos, desarrollo, integraciones, cloud o ninguna de ellas.
7. **Punto de partida** — iniciación, prototipos/herramientas, programación/integración o aplicaciones desplegadas y mantenidas.
8. **Tipo de reto que atrae** — entender la necesidad, encontrar patrones, construir una experiencia digital o conectar componentes fiables.
9. **Forma de aprender** — acompañamiento frecuente, flexibilidad o mezcla de estructura y ritmo propio.
10. **Disponibilidad semanal** — bloques cortos variables, varias horas regulares o bloques fijos y tiempo amplio.
11. **Resultado que quiere demostrar** — respuesta abierta.
12. **Titulación universitaria** — sí, quiere incluir la opción en la recomendación; o no, no es un factor decisivo.

## Recomendaciones disponibles

| Clave | Ruta mostrada | Enlace del programa | Dossier | PowerCalendar | Opción universitaria |
| --- | --- | --- | --- | --- | --- |
| `makers` | Intensive Makers | [Programa](https://thepower.education/thepowermba/intensive-makers) | [Dossier](https://thepower.education/forms/inmk-es-mql-dossier?previoussource=) | [Hablar con un orientador académico](https://powercalendar.tools.thepower.education/orientacion?programId=intensive-makers) | Intensive Makers + Programa Universitario |
| `rock` | Rock The AI Code | [Programa](https://thepower.education/thepowermba/tech/rock-the-code) | [Dossier](https://thepower.education/forms/rtc-es-mql-pdf?previoussource=) | [Hablar con un orientador académico](https://powercalendar.tools.thepower.education/orientacion?programId=rock-the-ai-code) | No se presenta como Intensive; queda fuera cuando la titulación es prioritaria |
| `agentic` | AI Agentic Developer | [Programa](https://thepower.education/thepowermba/tech/ai-agentic-developer) | [Dossier](https://thepower.education/forms/datp-es-desarrollador-agentico-mql-dossier?previoussource=) | [Hablar con un orientador académico](https://powercalendar.tools.thepower.education/orientacion?programId=intensive-agentic-ai-developer) | Intensive Master - Agentic AI Developer + Programa Universitario |
| `engineer` | AI Engineer | [Programa](https://thepower.education/thepowermba/tech/ai-engineer) | [Dossier](https://thepower.education/forms/tpie-es-aiengineer-mql-dossier?previoussource=) | [Hablar con un orientador académico](https://powercalendar.tools.thepower.education/orientacion?programId=intensive-ai-engineer) | Intensive AI Engineer + Programa Universitario |
| `data` | Máster en AI Data Analytics | [Programa](https://thepower.education/thepowermba/tech/data-analytics) | [Dossier](https://thepower.education/forms/tpda-es-mql-dossier?previoussource=) | [Hablar con un orientador académico](https://powercalendar.tools.thepower.education/orientacion?programId=intensive-ai-data-analytics) | No se ofrece como ruta con Programa Universitario en este orientador |

Power BI no es una ruta independiente del orientador. La descripción de AI Data Analytics incluye caminos de Business Intelligence o Analytics Engineering.

## Cómo se calcula

El motor suma puntos por programa para las respuestas de contexto, resultado esperado, experiencia práctica, punto de partida, tipo de reto, formato de aprendizaje y disponibilidad. La pregunta sobre nivel de estudios no aporta puntos ni altera el resultado. Las respuestas abiertas reciben pequeños impulsos por palabras relacionadas con automatización/procesos, datos/análisis, desarrollo de producto, agentes y despliegue/arquitectura.

La experiencia ajusta las rutas técnicas: no haber creado soluciones reduce la puntuación de AI Agentic Developer y AI Engineer; haber hecho prototipos sencillos también reduce esas rutas. Si la persona está empezando y la puntuación apunta a una ruta técnica avanzada, se propone Rock The AI Code como entrada progresiva. Cuando se prioriza la titulación universitaria, ese ajuste dirige a Intensive Makers.

La segunda ruta solo se muestra cuando su puntuación queda suficientemente cerca de la primera. La explicación final combina la prioridad, el caso escrito, el punto de partida, las actividades prácticas, el formato y el tiempo disponible.

### Preferencia por titulación universitaria

Responder “Sí” aplica dos cambios:

1. El ranking solo considera rutas Intensive con `universityLabel`. AI Data Analytics queda fuera de este filtro porque no es un programa Intensive con la opción indicada en esta evaluación.
2. El resultado muestra el nombre combinado, por ejemplo **Intensive Makers + Programa Universitario**, y explica que la ruta permite añadir esa opción.

Responder “No” deja disponible todo el catálogo de rutas y no añade la titulación al nombre recomendado.

## Notas de implementación

- El modelo de respuestas guardado usa la versión 5; las respuestas de versiones anteriores no se restauran para evitar desajustes con el nuevo orden de preguntas.
- Los botones del dossier y PowerCalendar abren destinos por programa; las citas llevan un `programId` específico.
- El razonamiento es determinista y basado en reglas. Aunque el texto se adapta a las respuestas, todavía no hay generación por IA.
