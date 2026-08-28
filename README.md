# .github

Este repositorio contiene los **archivos por defecto de la organización ParcoApp**.

Los archivos aquí se aplican automáticamente a cualquier repositorio de la organización
que no tenga su propia versión. Así mantenemos plantillas y políticas consistentes en un solo lugar.

## Contenido

- `profile/README.md` — perfil de la organización (interno).
- `.github/ISSUE_TEMPLATE/` — plantillas y configuración para reportar issues.
- `.github/pull_request_template.md` — plantilla de PR por defecto.
- `.github/PULL_REQUEST_TEMPLATE/lambdas.md` — plantilla de PR para lambdas (`?template=lambdas.md`).
- `workflow-templates/` — starter workflows de GitHub Actions.
- `SECURITY.md` — cómo reportar vulnerabilidades.

> Nota: ISSUE_TEMPLATE y PULL_REQUEST_TEMPLATE deben vivir dentro de una carpeta
> `.github/` anidada (`.github/.github/...` en este repo) para heredarse en toda la
> organización; el resto de archivos sí funcionan en la raíz.

## Cómo sobrescribir un default

Si un repositorio necesita su propia versión de alguno de estos archivos,
basta con crear ese archivo dentro del repositorio: su versión local tendrá prioridad
sobre el default de la organización.
