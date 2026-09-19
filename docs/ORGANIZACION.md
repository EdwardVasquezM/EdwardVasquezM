# Organización y revisión del repositorio

Fecha: 2026-09-19. Base inspeccionada: `f2380104b689a04ba399032f895d8f2b5b3a508e`.

## Clasificación conceptual

**Portafolio público · perfil**. Esta clasificación no modifica la visibilidad del repositorio.

## Metadatos propuestos para About

Descripción:

> Perfil profesional y guía de proyectos de Edward Vásquez Morales: ingeniería estructural, simulación y aprendizaje.

Topics:

`github-profile`, `structural-engineering`, `simulation`, `numerical-methods`, `engineering`.

Estos metadatos son una propuesta documentada. No se han aplicado a la configuración de GitHub; fusionar este PR no los aplica automáticamente.

## Hallazgos y decisiones

- El README anterior describía la presentación de Real Plaza y archivos inexistentes en este repositorio de perfil; se sustituyó por una presentación profesional y enlaces verificados.
- La estructura original contenía únicamente README.md; no se requieren carpetas de código ni herramientas de compilación.
- No se incluyen nombres, rutas ni contenido de repositorios privados en el perfil público.
- Los grupos son una organización conceptual; no cambian visibilidad ni permisos de GitHub.

## Higiene y documentación

Se añade un .gitignore limitado a temporales del sistema, archivos de bloqueo de Office y configuración local de secretos. No excluye modelos, resultados, CSV, imágenes ni documentos de ingeniería de forma global.

No se encontró licencia en la base inspeccionada. La selección de una licencia y los permisos de recursos de terceros quedan por definir por su titular.

No se eliminan ni renombran archivos. Comparación de SHA de los archivos existentes: sin duplicados exactos detectados dentro de este repositorio. Esta comprobación no identifica similitud semántica, visual ni duplicados entre repositorios.

## Verificación y límites

Revisión del árbol completo y de los archivos de texto pertinentes: README cuando existía, HTML, JavaScript y CSS según el repositorio. Se comprobó la ausencia de .gitignore y documentación complementaria en la base.

Los cambios de este PR se limitan a README.md, .gitignore y este documento. Se debe comprobar que el diff conserve los archivos originales restantes y que los enlaces relativos nuevos resuelvan.

No se ejecutaron aplicaciones, no se inspeccionaron visualmente imágenes o presentaciones y no se validaron resultados de ingeniería. Las propuestas funcionales y de revisión técnica anteriores quedan pendientes; no deben interpretarse como correcciones ya implementadas.
