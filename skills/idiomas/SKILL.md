---
name: idiomas
description: Sistema proactivo de idiomas. Gus recuerda estudiar, guarda vocabulario en Docs y hace repasos sorpresa aleatorios.
---

# Tracker de Idiomas y Aprendizaje

Sistema 100% automatizado para proteger el hábito de estudio de idiomas de Sue. Gus toma la iniciativa por Telegram, gestiona los apuntes en Docs y refuerza la memoria con repasos aleatorios.

## Flujo Proactivo (Disparadores de Tiempo)

### 1. Recordatorio de Estudio (13:00 y 21:00)
- A las 13:00 y a las 21:00 en punto, Gus envía un mensaje a Telegram por iniciativa propia.
- **Mensaje:** Un recordatorio motivador y amigable (ej. "¡Hola Sue! 🐶🌸 Es hora de tu sesión de Duolingo, ¡tú puedes!").

### 2. Seguimiento de Vocabulario (13:30 y 21:30)
- A las 13:30 y a las 21:30, Gus envía un segundo mensaje a Telegram.
- **Mensaje:** "¿Ya terminaste tu lección? Dime, ¿qué palabras nuevas aprendiste hoy?"

### 3. Repaso Sorpresa (Horarios Aleatorios)
- En momentos aleatorios del día, Gus lee al azar una palabra guardada en `Vocabulario_Frances` o `Vocabulario_Japones`.
- **Mensaje:** Envía un mensaje espontáneo a Telegram recordando la palabra, su significado y dándole a Sue un ejemplo práctico o contexto de cómo usarla. (Ej. "¡Bonjour, Sue! 🐶🌸 Recuerda que 'eau' significa agua. ¡Ideal para pedirla cuando termines tu WOD de CrossFit!").

## Flujo Reactivo (Cuando Sue responde)

### 4. Archivo en Docs (Google Drive)
- Cuando Sue responda con el vocabulario nuevo en Telegram, Gus identifica si es francés o japonés.
- Gus busca los documentos `Vocabulario_Frances` y `Vocabulario_Japones` en Drive (y los crea si no existen).
- Añade las palabras al final del documento correspondiente con el formato: `- [Palabra original]: [Traducción]`.
- Gus confirma por Telegram que el vocabulario está guardado.

## Gotchas
- **Nunca sobrescribas** el contenido anterior en Docs; usa siempre modo "append" (añadir al final).
- Si Sue envía palabras sin traducción, infiere el significado en español antes de guardarlo.
- Los repasos sorpresa deben ser muy breves, conversacionales y sin parecer lecciones aburridas.