# CodeMaster

Plataforma gamificada para aprender programación con un tiburón como mentor.

## Incluye
- 20 lenguajes/áreas.
- 90 misiones por lenguaje = 1.800 misiones.
- 6 etapas de dificultad.
- 6 Boss Battles por lenguaje = 120 en total.
- 80% práctica / 20% teoría.
- XP, vidas, progreso local, cursos, misiones, estadísticas, logros y perfil.
- Pantalla de carga con tiburón y animaciones de feedback.
- Monorepo con web, API, desktop, worker de ejecución, Prisma, Docker y tests.

## Estructura
```text
apps/
  api/
  desktop/
  execution-worker/
  web/
packages/
  config/
  database/
  shared/
content/
docker/
docs/
tests/
.github/
.vscode/
```

## Inicio rápido
1. Instala Node.js LTS.
2. Ejecuta `npm install`.
3. Ejecuta `npm test` para validar el contenido.
4. Ejecuta `npm run build:web` para construir la interfaz web.
5. Para API/Prisma/Docker, completa `.env.example` y la configuración local descrita en `docs/`.

## Seguridad
Nunca subas `.env`, credenciales, tokens o secretos. El worker está diseñado como contrato para ejecutar código únicamente dentro de un sandbox aislado; antes de producción debe conectarse a un runtime Docker real con límites de CPU/RAM/tiempo, sin red ni montajes del host.

## GitHub
Esta carpeta está preparada para subir su contenido al repositorio existente. Consulta `docs/GITHUB_SETUP.md`.
