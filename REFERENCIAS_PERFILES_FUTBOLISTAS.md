# Referencias de perfiles de futbolistas para inspirar la mejora del index

Este documento recoge páginas y referencias visuales de perfiles de jugadores para analizar prácticas recomendadas y luego aplicar mejoras al proyecto actual.

## Objetivo

Estudiar ejemplos de perfiles de futbolistas para extraer patrones útiles en:

- estructura del hero principal
- jerarquía visual del nombre y apellido
- organización de estadísticas
- uso de secciones de trayectoria, estilo y logros
- calidad visual y claridad de lectura
- composición tipográfica y espaciado

## Referencias a revisar

### 1) Transfermarkt
- https://www.transfermarkt.es/enner-valencia/profil/spieler/190199
- https://www.transfermarkt.com/

Patrones útiles:
- fuerte jerarquía del nombre del jugador
- bloques de información compactos y ordenados
- estadísticas muy claras y legibles
- enfoque en datos objetivos y perfil profesional

### 2) ESPN
- https://www.espn.com.mx/futbol/jugador/_/id/142356/enner-valencia
- https://www.espn.com.mx/futbol/

Patrones útiles:
- narrativa deportiva muy clara
- secciones fáciles de escanear
- paneles con datos por categoría
- presentación visual orientada al consumo rápido

### 3) Goal
- https://www.goal.com/es
- https://www.goal.com/es/noticias/enner-valencia/1f5x3qj9w6f2n1k7d1y7f0b1q

Patrones útiles:
- uso de contenido editorial con ritmo visual
- resúmenes rápidos y lectura ágil
- enfoque en contexto deportivo y perfil del jugador

### 4) Marca / Mundo Deportivo / AS
- https://www.marca.com/futbol.html
- https://www.mundodeportivo.com/futbol
- https://as.com/futbol/

Patrones útiles:
- alta densidad informativa sin perder claridad
- combinación de texto, foto y números
- estructura deportiva muy reconocible

### 5) Clubes / perfiles oficiales
- https://www.realmadrid.com/es-ES
- https://www.fcbarcelona.com/
- https://www.bocajuniors.com.ar/

Patrones útiles:
- estilo institucional premium
- gran cuidado de identidad visual
- composiciones más elegantes y menos cargadas

## Qué tomar del análisis

### Buenas prácticas que sí conviene aplicar
- Hero principal con foto grande y texto fuerte
- nombre principal muy visible, con apellido complementario
- bloques de stats organizados y homogéneos
- secciones separadas por objetivos claros: perfil, estilo, trayectoria, logros
- uso de espaciado consistente para evitar saturación visual
- navegación corta y directa
- contrastes altos para legibilidad

### Qué evitar
- demasiada información sin jerarquía clara
- secciones muy largas sin separación visual
- paletas que rompen la consistencia por detalles aislados
- textos demasiado pequeños para datos secundarios
- botones poco contrastados o sin distinción visual

## Observación sobre el proyecto actual

El proyecto actual ya tiene una base sólida en estructura y contenido, especialmente en:

- la narrativa del jugador
- la organización por secciones
- el uso de tabs para datos secundarios
- la atención a accesibilidad con skip links y foco visible

Sin embargo, en su versión base se puede mejorar:

- consistencia cromática
- jerarquía del h1 y del apellido
- equilibrio visual entre foto y contenido
- limpieza general de cards y bloques de métricas
- reducción de peso visual en algunas áreas

## Conclusión preliminar

Para mejorar el index, lo más valioso es tomar de estas referencias:

- la claridad de Transfermarkt para estadísticas
- la lectura rápida de ESPN/Goal para perfiles deportivos
- la elegancia visual de clubes oficiales para composición general

La idea es combinar:

- la precisión de datos de Transfermarkt
- la claridad editorial de ESPN
- la pulcritud visual de un perfil oficial de club

## Revisión de sincronización actual: HTML vs CSS

La estructura principal del documento HTML y la hoja de estilos está alineada en general, ya que el CSS define clases como:

- .topbar
- .brand
- .nav
- .hero
- .player-photo
- .hero-stats
- .button
- .card
- .timeline
- .feature-grid
- .detail-box

Esto indica que el HTML y el CSS están sincronizados en términos de nombres de clases y estructura semántica.

Sin embargo, hay un detalle importante: en la versión base, el `h1` tiene `color: red`, lo que rompe la consistencia visual del esquema de color general. Eso conviene corregir para mantener una identidad visual más coherente.

En resumen:
- sí están sincronizados funcionalmente
- pero no están del todo alineados visualmente en algunos detalles puntuales

## Siguiente paso sugerido

La siguiente etapa será:

1. revisar estas referencias visuales
2. definir una dirección visual mejor
3. aplicar correcciones de claridad y consistencia al index actual
4. preparar una versión final más pulida, con mejor jerarquía y mejor UX
