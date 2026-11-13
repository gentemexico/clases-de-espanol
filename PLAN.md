# Plan de estudio · Clases de Español

Alumno: código **E01** (17 años, angloparlante nativo, EE. UU.). Prioridad: voz, pronunciación, fonética y conversación.
Sitio: https://gentemexico.github.io/clases-de-espanol/ · Registro: hoja «Clases de Español · Progreso (Respuestas)» (Drive id `1I7c9bPywKEX5Pq51xO542LOLjDVorWhfUsWMNEhcfIk`).

## Cómo leer el registro
- Cada fila de la hoja trae en la columna `data` un arreglo JSON de eventos.
- Solo cuentan los eventos con `stu = "E01"`. Se excluyen `TUTOR`, `TEST` y los dispositivos de prueba `x07zu379`, `jiywl6d9`, `5ch4uoks` (pruebas del 12-nov-2026).
- Eventos: `open`/`leave` (con `snap`, foto completa del progreso), `view`, `step`, `answer`, `set_done`, `lesson_done`, `comp_done`, `ear`, `talk`, `word_check`, `word_review`, `project`, `placement_done`, `confidence`, `hw_tick`, `record`, `summary_copied`.
- El último `snap` de E01 es la fuente de verdad del estado.

## Estado del plan
| Clase | Fecha | Contenido | Estado |
|---|---|---|---|
| 1 | 10-nov-2026 | Lección 1 «My world in Spanish»: verbos -ar (yo/tú/él/ella) | Hecha |
| 2 | 12-nov-2026 | Lección 2 «All about me»: me llamo, soy de, tengo … años, vivo en, me gusta; examen de colocación | En curso |
| 3 | Por definir | Se decide con el examen de colocación y el registro | Pendiente |

## Supuesto vigente
«Principiante desde cero» hasta tener el resultado del examen de colocación.

## Reglas para ajustar el plan
- Errores repetidos en un tema (2 o más primeros intentos fallidos) → refuerzo en la tarea siguiente.
- Prueba de oído < 70 % en un sonido → ese sonido entra a la tarea.
- `word_check` con palabras no captadas repetidas → práctica de pronunciación de esas palabras.
- Cambios al sitio (lección nueva, tarea nueva) los aprueba el tutor antes de publicarse.

## Bitácora de reportes

### Reporte 13-nov-2026 (actividad del 12-nov, hora del Pacífico)
- **Sesiones:** 1 sesión real, 16:45–17:38 (≈ 53 min). Además, una apertura a las 18:34 sin actividad. Las aperturas de 12:42–13:01 cerraron en menos de 1 s, cada una con un dispositivo nuevo: parecen cargas de prueba y no se cuentan.
- **Warm-up (repaso de la Lección 1):** 8/8 sin errores (palabras, imagen, escucha, gramática -ar). Habló bien: «Tú escuchas música.» lo captó completo.
- **Lección 2, paso 3:** set de práctica con 8/8 aciertos a primer intento, pero **3/8 sin ayuda**. Pidió ayuda o el significado en p1 (no me gusta), p3 (yo soy de), p5 (tú vives), p6 (¿cómo te llamas?) y p7 (ella es).
- **Lectura y escucha:** entró a «Listen», pero no hay reproducciones registradas. No hizo conversación, prueba de oído, mini proyecto ni marcó palabras «Still learning».
- **Examen de colocación:** no aparece. **Tarea (hw):** 0/7.
- **Errores repetidos:** ninguno (cero primeros intentos fallidos). Patrón de ayuda: **ser** (soy/es, 2 veces) y **terminaciones de tú** (vives/llamas, 2 veces).
- **«Check my words»:** en «Hola, me llamo Alex.» solo cambió «Alex» por su propio nombre. Eso es correcto, no es un error de pronunciación.
- **Alerta técnica:** los eventos de la sesión llegaron sin dispositivo ni sesión (`dev`/`ses` nulos) y el último `snap` (18:34) muestra todo en cero (paso 0, sin sets). Puede ser otro navegador o un modo que no guarda. Hay que revisarlo antes de confiar en el `snap`.
- **Ajustes propuestos para la clase 3 (los aprueba el tutor):**
  1. Primero, el examen de colocación (sigue pendiente); el supuesto sigue en «principiante desde cero».
  2. Refuerzo corto de ser (yo soy / tú eres / él-ella es) y de las terminaciones de tú (-as/-es) en la tarea: 4 a 6 ítems sin el botón de significado. No llega a la regla de 2 fallos, pero dependió de la ayuda en los dos temas.
  3. Terminar la Lección 2 con la parte de voz: conversación «All about me» con sus propios datos y la prueba de oído, que todavía no hace, para aplicar la regla del 70 %. Además, revisar el guardado del progreso: que `open` traiga `dev` y que el `snap` refleje los pasos.
