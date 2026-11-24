<!-- BEGIN:nextjs-agent-rules -->

## This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` (resolved from this file's directory; in monorepos the `next` package may not be visible from the repo root) before writing any code. Heed deprecation notices.

This block is written and re-added by `next dev` — verify at `node_modules/next/dist/server/lib/generate-agent-files.js`. Removing it from a diff only re-creates the uncommitted change; committing it with your work keeps the tree clean.


## Reglas del proyecto (Fisiorol)

- Sitio con exportación estática (`output: "export"`): no uses rutas de API
  ni middleware de Next.js. Los datos dinámicos vienen del backend FastAPI.
- TypeScript estricto: no uses `any`.
- Componentes de servidor por defecto; `"use client"` solo si hay estado
  o eventos.
- HTML semántico, accesible y mobile-first (probar en 360px de ancho).
- Textos en español de Perú.
- No agregues dependencias sin preguntarme primero.
- No inventes datos del negocio (teléfono, precios, horarios, textos médicos):
  si falta un dato, déjalo marcado como TODO.

<!-- END:nextjs-agent-rules -->
