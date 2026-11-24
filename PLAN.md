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

### Reporte 14-nov-2026 (actividad del 13-nov, hora del Pacífico)
- **Sesiones:** 0 sesiones con actividad. Solo 2 aperturas (00:05 y 00:08), cada una con un dispositivo nuevo, sin `leave`, sin vistas ni respuestas. Tiempo útil: ≈ 0 min.
- **Qué hizo:** nada registrado: sin pasos, sets, lectura/escucha, conversación, prueba de oído, «Still learning» ni mini proyecto.
- **Examen de colocación:** no aparece. **Tarea (hw):** 0/7.
- **Errores repetidos / «Check my words»:** sin datos nuevos.
- **Estado (último `snap`, 00:08):** todo en cero (Lección 2 en paso 0, sin sets ni warm-up), aunque el 12-nov ya hizo el warm-up 8/8 y el paso 3 de la Lección 2. **La alerta técnica sigue:** cada apertura llega con un `dev` nuevo y el `snap` no refleja el avance; el progreso no se está guardando entre visitas, así que el `snap` no sirve como fuente de verdad por ahora.
- **Ajustes propuestos para la clase 3 (los aprueba el tutor):**
  1. Antes de la clase, revisar el guardado del progreso en el navegador del alumno (modo privado, otro navegador o almacenamiento bloqueado); si no se corrige, que el alumno lo abra siempre desde el mismo navegador normal.
  2. Mantener el orden ya propuesto: examen de colocación primero, luego refuerzo de ser (soy/eres/es) y terminaciones de tú (-as/-es) sin botón de significado.
  3. Cerrar la Lección 2 con la conversación «All about me» y la prueba de oído (regla del 70 %), y dejar la tarea 1 asignada en clase para que haya al menos una casilla `hw` medible.

### Reporte 20-nov-2026 (actividad del 19-nov, hora del Pacífico)
- **Sesiones:** 1 visita corta, 12:45–12:46 (≈ 1 min). Sin `open`/`leave`: los eventos siguen llegando con `dev`/`ses` nulos. Del 14 al 18-nov no hubo actividad.
- **Qué hizo:** entró a la Lección 2 y usó «Check my words» con «Hola, me llamo Alex.»: captó todas las palabras (la transcripción incluyó un «Siri» al inicio, ruido del asistente de voz). Grabó la frase `ph0` (sin audio en el registro). Después solo navegó: Words, Listen, Progress, Words, Practice.
- **Sin datos de:** pasos nuevos, sets, reproducciones en lectura/escucha, conversación, prueba de oído, «Still learning» ni mini proyecto.
- **Examen de colocación:** no aparece. **Tarea (hw):** 0/7.
- **Errores repetidos:** ninguno nuevo. Sigue el patrón del 12-nov: dependencia de ayuda en **ser** (soy/es) y **terminaciones de tú** (vives/llamas).
- **«Check my words»:** 0 palabras no captadas. Mejora frente al 12-nov, cuando cambió «Alex» por su nombre.
- **Estado (último `snap`, 13-nov 00:08):** todo en cero. No hay `snap` nuevo desde entonces; **la alerta técnica sigue**: el progreso no se guarda y el `snap` no sirve como fuente de verdad.
- **Ajustes propuestos para la clase 3 (los aprueba el tutor):**
  1. Corregir el registro antes de la clase: que cada visita mande `open` con `dev` estable y `snap` (revisar navegador del alumno: modo privado o almacenamiento bloqueado).
  2. Hacer el examen de colocación en la clase, acompañado; lleva 8 días pendiente y el plan sigue en «principiante desde cero».
  3. Aprovechar que ya graba y habla: cerrar la Lección 2 con la conversación «All about me» y la prueba de oído (regla del 70 %), más 4–6 ítems de ser (soy/eres/es) y tú (-as/-es) sin botón de significado; asignar la tarea 1 en clase.

### Reporte 23-nov-2026 (actividad del 23-nov, hora del Pacífico)
- **Sesiones:** 1 visita corta, 08:33–08:35 (≈ 2 min). Sin `open`/`leave`: los eventos siguen llegando con `dev`/`ses` nulos. Del 20 al 22-nov no hubo actividad.
- **Qué hizo:** Home → Lessons → Words → Listen. En Listen usó «Check my words» con «hola» y lo captó completo. Nada más.
- **Sin datos de:** pasos nuevos, sets, reproducciones en lectura/escucha, conversación, prueba de oído, «Still learning» ni mini proyecto.
- **Examen de colocación:** no aparece (11 días pendiente). **Tarea (hw):** 0/7.
- **Errores repetidos:** ninguno nuevo. Sigue el patrón del 12-nov: dependencia de ayuda en **ser** (soy/es) y **terminaciones de tú** (vives/llamas).
- **«Check my words»:** 0 palabras no captadas (tercera vez seguida sin fallos, aunque hoy fue una sola palabra).
- **Estado (último `snap`, 13-nov 00:08):** todo en cero; no hay `snap` nuevo. **La alerta técnica sigue** (cuarto reporte): el progreso no se guarda y el `snap` no sirve como fuente de verdad.
- **Ajustes propuestos para la clase 3 (los aprueba el tutor):**
  1. Prioridad técnica: corregir el registro (que cada visita mande `open` con `dev` estable y `snap`); sin eso no se puede medir la tarea ni el avance.
  2. Las visitas sueltas son de 1–2 min y solo exploran: hacer la clase 3 acompañada, con el examen de colocación al inicio.
  3. Cerrar la Lección 2 en clase: conversación «All about me», prueba de oído (regla del 70 %) y 4–6 ítems de ser (soy/eres/es) y tú (-as/-es) sin botón de significado; dejar asignada la tarea 1 con una meta corta y diaria (5 min).
