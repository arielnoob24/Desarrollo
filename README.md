# Enner Valencia - Perfil

Sitio web estático sobre el perfil de Enner Valencia.

## CI/CD

Este repositorio incluye un workflow de GitHub Actions para:

- validar que el archivo HTML y el CSS existan y sean válidos;
- desplegar automáticamente la página en GitHub Pages cuando se hace push a la rama `main`.

## Requisitos

- GitHub repository con Pages habilitado.
- Rama principal llamada `main`.

## Estructura

- `index.html`: contenido principal del sitio
- `styles.css`: estilos del sitio
- `.github/workflows/ci-cd.yml`: pipeline de integración y despliegue continuo
