# 🦈 CodeMaster

Plataforma de aprendizaje de programación con una experiencia inspirada en la gamificación, práctica guiada y progresión por misiones.

> **Estado:** base de desarrollo / prototipo funcional. La arquitectura está preparada para continuar la integración de Electron, API, PostgreSQL/Prisma, ejecución aislada y contenido didáctico completo.

## ✨ Incluye

- 20 lenguajes/áreas.
- 90 misiones por lenguaje: **1.800 misiones estructuradas**.
- 6 etapas progresivas: fundamentos → experto.
- Boss Battle cada 15 misiones.
- Metodología de aprendizaje activo **80% práctica / 20% teoría**.
- Tiburón como mascota/mentor.
- Pantalla de carga con tiburón saltando del mar.
- XP, vidas, progreso y feedback de ejercicios.
- Estructura para cursos, lecciones, proyectos, misiones, logros, estadísticas y leaderboard.
- API Node/TypeScript.
- Prisma/PostgreSQL.
- Worker de ejecución aislada.
- Docker.
- Electron.
- Tests y CI de GitHub.

## 🧰 Stack objetivo

- Electron
- React / Vite
- TypeScript
- Node.js 20+
- PostgreSQL
- Prisma
- Monaco Editor
- Docker
- Vitest / Playwright

## 🚀 Instalación local

```bash
npm install
```

Copia las variables de ejemplo:

```bash
# Windows PowerShell
Copy-Item .env.example .env

# macOS/Linux
cp .env.example .env
```

Edita `.env` con valores locales. **No subas `.env` a GitHub.**

## ▶️ Desarrollo

Frontend web:

```bash
npm run dev
```

API:

```bash
npm run api:dev
```

Worker:

```bash
npm run worker:dev
```

Desktop:

```bash
npm run desktop:dev
```

## 🧪 Validación

```bash
npm test
npm run build
npm run lint
```

Los scripts disponibles dependen de la configuración actual de cada workspace; si un script aún no está definido en un workspace, debe implementarse antes de considerarlo parte del pipeline de producción.

## 🐳 Docker

```bash
docker compose up -d
```

Para detenerlo:

```bash
docker compose down
```

## 📚 Contenido

La definición estructurada de las misiones se encuentra en `content/`. El currículo está documentado en `CURRICULUM.md`.

## 🔐 Seguridad

Consulta `SECURITY.md`. Nunca ejecutes código de usuario sin aislamiento, límites de CPU/RAM/tiempo y sin acceso al host o secretos.

## 🌊 Referencia de UX

`VIDEO_REFERENCE.md` documenta los patrones de interacción tomados como referencia para adaptar la experiencia al tiburón de CodeMaster.

## 🐙 GitHub

Guía paso a paso para publicar el proyecto desde VS Code:

`docs/GITHUB_SETUP.md`

Estructura recomendada del repositorio:

`docs/GITHUB_STRUCTURE.md`

## 📄 Licencia

Añade una licencia antes de distribuir CodeMaster públicamente si corresponde a tu proyecto.
