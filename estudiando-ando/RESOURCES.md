# HTTP y APIs — Recursos

## Knowledge

- [MDN: HTTP request methods](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Methods)
  Referencia oficial y autoritativa de GET/POST/PUT/PATCH/DELETE, idempotencia y seguridad de cada método. Use for: fuente primaria de la Lección 1, y para saldar cualquier duda de "¿qué método es el correcto acá?".
- [MDN: An overview of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)
  Panorama general de cómo funciona la conversación cliente-servidor. Use for: anatomía de una request/response, terminología base (headers, body, status).
- [n8n Docs: HTTP Request node](https://docs.n8n.io/integrations/builtin/core-nodes/n8n-nodes-base.httprequest)
  Documentación de la herramienta que Nico ya usa en producción (FastPass). Use for: conectar la teoría con el HTTP Request node real — método, auth, params/headers/body en la UI de n8n.
- [MDN: HTTP response status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Status)
  Referencia oficial de las clases 2xx/3xx/4xx/5xx y cada código individual. Use for: fuente primaria de la Lección 2, y para resolver "¿de quién es la culpa, cliente o servidor?".
- [MDN: Authorization header](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/Authorization)
  Referencia oficial del header que lleva las credenciales (Basic, Bearer, etc.). Use for: fuente primaria de la Lección 3 — cómo una API sabe quién sos.
- [MDN: Content-Type header](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/Content-Type)
  Referencia oficial del header que declara el formato del body. Use for: el bug clásico de mandar JSON sin avisarlo, cubierto en la Lección 3.

- [GitHub Docs: Authenticating to the REST API](https://docs.github.com/en/rest/authentication/authenticating-to-the-rest-api)
  Cómo mandar un Personal Access Token (`Authorization: Bearer`), qué devuelve con token inválido (401) y por qué a veces un 403/404 es falta de permisos. Use for: fuente primaria de la Lección 5.
- [n8n Docs: HTTP Request credentials](https://docs.n8n.io/integrations/builtin/credentials/httprequest/)
  Cómo configurar Header Auth (Name/Value) en el HTTP Request node. Use for: guardar tokens en Credentials de n8n en vez de pegarlos en el nodo.

- [GitHub Docs: Using pagination in the REST API](https://docs.github.com/en/rest/using-the-rest-api/using-pagination-in-the-rest-api)
  `per_page`/`page` y el header `link`. Use for: paginación por número de página (Lección 6).
- [Gmail API: users.messages.list](https://developers.google.com/workspace/gmail/api/reference/rest/v1/users.messages/list)
  `maxResults` (100 por defecto, 500 máx), `pageToken`/`nextPageToken`, `q`. Use for: paginación por token, directo al caso de FastPass.

## Gaps

- Falta recurso sobre el **flujo de OAuth2** (el intercambio con redirects) — sigue fuera de alcance en [[MISSION]]; la Lección 3 cubre Basic Auth y API Key/Bearer token, que alcanza para lo que Nico usa hoy en n8n.

## Wisdom (Communities)

- Pendiente. No se preguntó todavía si Nico quiere sumar una comunidad (ej. r/webdev, foros de n8n). Retomar en próxima sesión — ver [[NOTES]].
