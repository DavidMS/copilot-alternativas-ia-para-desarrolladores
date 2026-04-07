# Cuestionario Sesión 1: IA en Desarrollo — Temas 1 y 2

https://forms.gle/MfVPgbHnn4UUcMvQ7

---

**Pregunta 1.** ¿Cuál es la principal limitación del modelo de asistencia de la Era 1 (Autocomplete)?

- A) No puede generar código en Java
- B) Solo funciona en VS Code, no en IntelliJ
- C) No tiene acceso al contexto global del proyecto ni puede ejecutar comandos para verificar su sugerencia
- D) Requiere conexión a internet para funcionar

---

**Pregunta 2.** El problema conocido como "The Copy-Paste Gap" describe:

- A) La dificultad de copiar código entre diferentes lenguajes de programación
- B) El ciclo manual de copiar código del chat, pegarlo en el IDE, verificar compilación y volver al chat cuando hay errores
- C) Un bug en GitHub Copilot que duplica código al autocompletar
- D) La imposibilidad de copiar configuraciones entre proyectos Spring Boot

---

**Pregunta 3.** En la Era 3 (Agentes), ¿cuál es el nuevo rol del desarrollador respecto a las eras anteriores?

- A) Escribir código más rápido usando atajos de teclado
- B) Revisar código generado por otros desarrolladores del equipo
- C) Actuar como arquitecto y revisor: escribe la especificación y guía al agente
- D) Ejecutar manualmente los tests de integración que el agente genera

---

**Pregunta 4.** ¿Qué característica diferencia fundamentalmente a los agentes de terminal (como Claude Code) respecto a los modelos de chat?

- A) Los agentes de terminal solo funcionan con proyectos Maven, no Gradle
- B) Pueden leer el proyecto completo, ejecutar comandos (`mvn`, `docker`, `git`) e iterar sobre errores de compilación
- C) Tienen una ventana de contexto mayor que los modelos conversacionales
- D) Son exclusivamente gratuitos y de código abierto

---

**Pregunta 5.** GitHub Copilot en modo agente (VS Code) permite:

- A) Únicamente usar GPT-4o como modelo subyacente
- B) Seleccionar el modelo subyacente entre varias opciones (Claude Sonnet, GPT-4o, Gemini, etc.)
- C) Ejecutar comandos de terminal directamente sin confirmación del desarrollador
- D) Conectarse a bases de datos de producción para generar código adaptado a los datos reales

---

**Pregunta 6.** ¿Para qué tipo de tarea está indicado principalmente el tier de modelo "razonamiento profundo" (Claude Opus, o1)?

- A) Generación de mappers, getters/setters y código boilerplate repetitivo
- B) Completado inline de código en el IDE
- C) Consultas puntuales sobre la sintaxis de una anotación Spring
- D) Diseño de arquitectura, evaluación de trade-offs y generación de ADRs

---

**Pregunta 7.** Usar siempre el modelo más potente (tier alto) para todas las tareas es un error porque:

- A) Los modelos potentes no entienden Spring Boot 3.x
- B) Genera coste innecesario en tareas simples, aumenta la latencia y agota el presupuesto de API en tareas de poco valor
- C) Solo funciona para proyectos con más de 100.000 líneas de código
- D) No es compatible con el plugin de IntelliJ para Claude Code

---

**Pregunta 8.** ¿Qué información **nunca** debe enviarse a un modelo de IA externo?

- A) El contenido de un fichero `pom.xml` con las dependencias del proyecto
- B) Un fragmento de código de un `UserController.java` con lógica de negocio no sensible
- C) Credenciales, tokens, contraseñas, datos PII de usuarios reales o claves privadas de infraestructura
- D) La estructura de paquetes de un proyecto con arquitectura hexagonal

---

**Pregunta 9.** El fichero `CLAUDE.md` en un repositorio cumple la función de:

- A) Cambiar automáticamente el modelo de IA que usa Claude Code de forma programática
- B) Almacenar las credenciales de API de Anthropic para el equipo
- C) Servir como "briefing" del proyecto: instrucciones en lenguaje natural que el agente lee automáticamente al iniciar la sesión
- D) Definir los endpoints REST del proyecto para que el agente los exponga automáticamente

---

**Pregunta 10.** Según la matriz de decisión del tema 2, ¿qué herramienta es la más adecuada cuando el criterio prioritario es la **privacidad máxima** del código?

- A) GitHub Copilot Pro+ ($39/mes)
- B) Claude Code con plan Enterprise
- C) JetBrains AI con Claude Agent integrado
- D) Un modelo autohospedado como Llama o Granite (sin salida de datos a terceros)

---

## Respuestas

| # | Respuesta correcta |
|---|---|
| 1 | C |
| 2 | B |
| 3 | C |
| 4 | B |
| 5 | B |
| 6 | D |
| 7 | B |
| 8 | C |
| 9 | C |
| 10 | D |
