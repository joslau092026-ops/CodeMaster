# CodeMaster v6 — Ultra Titan

Versión web estática de CodeMaster, una plataforma de aprendizaje de programación con una experiencia de ruta gamificada.

## Qué incluye

- Interfaz de aprendizaje inspirada en el modelo de rutas de aplicaciones educativas, con identidad visual propia.
- Mascota oficial **Byte**, tiburón tecnológico, integrada en inicio, onboarding, lecciones, ranking y perfil.
- Animaciones de Byte: flotación, movimiento lateral, burbujas y animación especial de celebración.
- Onboarding en 3 pasos:
  1. Introducción a CodeMaster.
  2. Elección del lenguaje principal.
  3. Explicación de XP, rangos y racha.
- **46 rangos** exactos:
  - Bronce I, II, III
  - Plata I, II, III
  - Oro I, II, III
  - Platino I, II, III
  - Zafiro I, II, III, IV
  - Rubí I, II, III, IV
  - Esmeralda I, II, III, IV
  - Amatista I, II, III, IV, V
  - Perla I, II, III, IV, V
  - Obsidiana I, II, III, IV, V
  - Diamante I, II, III, IV, V, VI
  - **ULTRA TITAN**
- **ULTRA TITAN requiere exactamente 100.000 XP** y tiene un diseño visual especial.
- Insignia del rango actual visible junto al usuario, en el inicio y en el perfil.
- Página de progreso con todos los rangos y sus requisitos de XP.
- Tabla de ranking ordenada por XP total, mostrando posición, usuario, rango, XP y racha.
- Perfil personal con cambio de foto de perfil.
- La foto se redimensiona en el navegador antes de guardarse para reducir su tamaño.
- XP protegida: los botones de navegación no entregan XP.
- Una lección solo entrega XP una vez y requiere responder correctamente.
- Racha diaria: completar una lección cuenta como actividad del día.
- Cursos incluidos: Python, JavaScript, HTML + CSS, Java y C++.
- Persistencia con `localStorage`.
- Migración automática desde la versión anterior que utilizaba `codemaster_pro_v2`.
- Diseño responsive para computador, tablet y móvil.

## Rangos y XP

Los umbrales están definidos en `app.js` dentro de `RANKS`. El último rango es:

**ULTRA TITAN — 100.000 XP**

## Cómo abrirlo

No requiere Node, npm ni servidor para probar la demo.

1. Descomprime el ZIP.
2. Abre `index.html` en el navegador.
3. Crea una cuenta.
4. Completa el onboarding.

## Importante sobre esta versión

La autenticación, el progreso, las fotos y el ranking son locales al navegador. Para una versión pública real con cuentas entre dispositivos y ranking mundial se necesita un backend y una base de datos, por ejemplo Supabase, Firebase o una API propia.

La contraseña de esta demo se almacena localmente para facilitar la prueba; no debe utilizarse así en producción.
