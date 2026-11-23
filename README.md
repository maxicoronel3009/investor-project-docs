# Investor AI — Presentación del proyecto

Sitio informativo en español de **Investor AI**, un proyecto personal de investigación financiera asistida por IA.

## Publicación con GitHub Pages

1. Configurá el repositorio como **público** desde **Settings → General → Danger Zone → Change repository visibility**.
2. Entrá en **Settings → Pages**.
3. En **Build and deployment**, seleccioná **Deploy from a branch**, rama **main**, carpeta **/(root)**.
4. Guardá los cambios y verificá el enlace publicado.

URL prevista: https://maxicoronel3009.github.io/investor-project-docs/

## Contenido

- Presentación y objetivos.
- Arquitectura multiagente.
- Agentes y tecnologías.
- Funcionalidades implementadas y trabajo en curso.
- Seguridad y roadmap.

Los repositorios de código `investor-agent` e `investor-mcp` permanecen privados. Esta web **no contiene** credenciales, tokens, archivos de cartera, documentos de brokers ni código propietario.

## Política de actualización

- Actualizar este sitio al completar hitos funcionales del MCP o del orquestador (idealmente cada 2–3 PRs), sin publicar datos de cartera ni secretos.
- Distinguir claramente funcionalidades integradas en `main`, PRs con CI aprobado pero pendientes de merge y funcionalidades planificadas.
- Documentar limitaciones importantes: no hay ejecución automática de operaciones, las valoraciones no son garantías de rendimiento y los snapshots privados no implican sincronización en vivo.
- Última revisión de avances: 23/11/2026 (MCP PR #31–36; #36 pendiente de merge al preparar esta actualización).

## Actualización

Editá `index.html` para modificar el contenido del sitio. Las funcionalidades en desarrollo se presentan como tales, sin dar por finalizadas pruebas que aún no se ejecutaron.
