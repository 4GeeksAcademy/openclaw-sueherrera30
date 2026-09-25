## Skill 1: Traker de idiomas y aprendizaje

**1. ¿Qué hace esta skill?**
Es un flujo automatizado que crea recordatorios diarios en Google Calendar (13:00 y 21:00), me contacta proactivamente por Telegram 30 minutos después de cada bloque para preguntarme qué aprendí, y archiva el vocabulario nuevo en Google Docs separados por idioma (francés y japonés), creando los archivos el primer día y editándolos los días siguientes.

**2. ¿Qué input necesita el agente?**
*   **Qué le doy:** 
    *   Para arrancar el sistema: Una instrucción simple como "Gus, activa mi rutina de Duolingo".
    *   Para el día a día: Mi respuesta en Telegram con las palabras nuevas (ej. "Hoy vi 'chien' en francés y 'neko' en japonés").
*   **Qué ya sabe:** A partir de los archivos de configuración, sabe conectarse a Google Calendar, enviar mensajes por Telegram, y crear/editar documentos en Google Drive. También sabe que su tono debe ser motivador.

**3. ¿Cómo es un buen output?**
*   **Formato y destino:** 
    1. Creación de eventos recurrentes en Calendar a las 13:00 y 21:00.
    2. Un mensaje proactivo automático de Gus en Telegram (ej. "¡Holi! ¿Terminaste tu lección? ¿Qué palabras nuevas viste hoy? 🐶🌸").
    3. Texto añadido a los archivos `Vocabulario_Frances` y `Vocabulario_Japones` en Docs.
*   **Cómo sabré que funcionó:** Veré los bloques en mi calendario, recibiré el mensaje de Gus sin tener que hablarle yo primero, y podré verificar mis listas de vocabulario actualizadas en Drive.


## Skill 2: Mentor de IA y Cloud

**1. ¿Qué hace esta skill?**
Envía proactivamente lecciones diarias progresivas (de básico a avanzado) sobre Inteligencia Artificial y conceptos de Google Cloud, incluye un mini-quiz, evalúa el resumen de dos líneas de Sue, guarda el aprendizaje en Google Docs y lanza un recordatorio de repaso cada mañana a las 8:30 AM.

**2. ¿Qué input necesita el agente?**
*   **Qué le doy:** 
    *   Activación automática por tiempo (cron/heartbeat a las 8:30 AM para repaso y a otra hora de la tarde para la lección nueva).
    *   Respuestas en Telegram de Sue contestando el quiz y escribiendo su resumen de dos líneas.
*   **Qué ya sabe:** Que Sue es Frontend Jr estudiando en 4Geeks, que ya tiene bases (Certificación Cloud Engineer Associate) pero necesita refrescarlas, y que aprende mejor con explicaciones fáciles, metáforas (música/CrossFit) y documentación anexa. 

**3. ¿Cómo es un buen output?**
*   **Formato y destino:** 
    1. Un mensaje en Telegram a las 8:30 AM recordando leer el concepto del día anterior.
    2. Un mensaje en Telegram en la tarde con la lección estructurada (Concepto fácil + Metáfora + Link a doc oficial + Mini-quiz).
    3. Un documento en Google Docs (ej. `Diario_Aprendizaje_IA_GCP`) que el agente actualiza cada noche añadiendo el concepto del día, la respuesta al quiz y el resumen de Sue.
*   **Cómo sabré que funcionó:** Recibiré mis lecciones y recordatorios sin pedirlos, Gus validará mis respuestas del quiz en el chat, y veré mi "Diario de Aprendizaje" creciendo solo en Google Drive.