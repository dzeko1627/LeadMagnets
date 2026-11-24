# Orientador de programas de IA · thePower

Prototipo interactivo para ayudar a una persona a encontrar el programa de tecnología e IA que mejor encaja con sus objetivos, experiencia y preferencias de aprendizaje. Está planteado como una experiencia de captación de leads: ofrece una orientación personalizada y, al final, permite consultar el programa, pedir su dossier o reservar una conversación informativa.

## Ejecutar en local

Desde la raíz del repositorio:

```bash
python3 -m http.server 3066
```

Abre `http://localhost:3066/` para la vista principal o `http://localhost:3066/mobile.html` para la vista móvil.

## Qué contiene

- `index.html`: cuestionario, cálculo de recomendación y resultado con enlaces al programa, dossier y PowerCalendar.
- `mobile.html`: marco de previsualización móvil que carga `index.html`.
- `docs/modelo-y-contenido.md`: preguntas, criterios de recomendación, programas y enlaces configurados.

## Alcance del prototipo

La recomendación actual usa puntuación determinista y una explicación construida a partir de las respuestas. No llama a un modelo de IA ni envía las respuestas a un servicio. Si la persona valora la titulación universitaria, la recomendación se limita a las rutas Intensive que ofrecen esa opción y añade “+ Programa Universitario” al nombre recomendado.

Los datos de la titulación universitaria describen la opción indicada para este prototipo. Condiciones, disponibilidad y detalles académicos deben confirmarse con el equipo del programa antes de publicar la experiencia.