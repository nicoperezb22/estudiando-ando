# Mission: HTTP y APIs

## Why
Nico ya usa APIs a ciegas en **FastPass** (n8n: Gmail → HTTP → Sheets) y va a necesitarlas de nuevo, más en serio, cuando arranque proyectos propios (EVACAKES, TURNA) e integre pagos, IA o servicios externos. De fondo, quiere que "las APIs" dejen de ser un punto débil de cara a conseguir empleo de dev. Prioridad declarada: primero n8n (lo que ya usa hoy), después proyectos propios, después entrevistas/empleo.

## Success looks like
- Puede explicar qué pasa "por debajo" cuando arma un HTTP Request node en n8n: método, URL, headers, body, y qué le vuelve en la respuesta.
- Frente a la documentación de una API nueva, elige el método correcto (GET/POST/PUT/PATCH/DELETE) sin dudar, justificando el porqué.
- Lee una respuesta de API (status code + body) y sabe si salió bien, mal, o por qué falló.
- El concepto le queda a largo plazo — no solo mientras lo está viendo.

## Constraints
- Ya vio HTTP/APIs "por arriba" antes y no le quedó (lo dice explícitamente: "me cuesta", "ya me olvidé"). Prioridad fuerte: **retención** (storage strength) por sobre cobertura rápida — ver [[0001-exposicion-previa-http]].
- Sesiones sueltas, sin cadencia fija todavía.
- Base ya sólida: JavaScript/Node.js, n8n en uso productivo (FastPass), arrancando con Next.js.

## Out of scope (por ahora)
- Autenticación avanzada (OAuth2, JWT) — se aborda después de dominar métodos y status codes.
- Diseñar una API propia (backend) — esto es sobre *consumir* APIs, no construirlas.
- Comparar librerías HTTP client (axios vs fetch vs otras) — solo si hace falta para un ejercicio puntual.
