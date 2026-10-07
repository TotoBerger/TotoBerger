# Hola, soy Tobías 👋

Desarrollador full stack y estudiante de Ingeniería en Informática en la Universidad Austral.
Trabajo en equipo sobre productos reales: apps móviles, APIs, aplicaciones web de gestión y herramientas de desarrollo.

> La mayoría de mi trabajo está en repositorios privados de organizaciones, por eso no se ve en mi lista de repos.
> Abajo hay un resumen de los proyectos en los que contribuí y/o contribuyo actualmente (algunos ya están terminados o inactivos).

### 🛠️ Stack

`TypeScript` `JavaScript` `React` `React Native` `Next.js` `Node.js` `PHP / Laravel` `Java / Spring` `Kotlin` `Python` `C# / Unity` `PostgreSQL` `MySQL` `Prisma` `Docker`

---

## 🚀 Proyectos principales

### 🏗️ Arquinering S.R.L.: sistema de gestión de obras
Aplicación web a medida para una constructora. Reemplaza las planillas Excel con las que se gestionaban las obras.
- **Migración de datos:** scripts en Python (openpyxl) que llevan las planillas de "Resumen de Obra" del formato legacy al nuevo modelo, con validación y recálculo.
- **Presupuestador:** armado de presupuestos por partidas y recetas, controles de consistencia entre costos y rubros, y exportación de un documento final en PDF/Excel para el cliente.
- **Control de presupuesto:** seguimiento de costos con ajuste por inflación (índice CAC) y cotización del dólar MEP, que se actualizan solas con un proceso diario.
- **Recursos:** importación de quincenas y cálculo de horas reales ponderadas.
- **Base de datos:** PostgreSQL con migraciones; diagnostiqué y corregí problemas de estabilidad del pool de conexiones y de queries que se colgaban.

### ♻️ Scrapy: startup de reciclaje
Plataforma que conecta a personas que quieren deshacerse de materiales reciclables con recicladores locales.
- **App móvil y API:** React Native/Expo y Laravel con OAuth2, más observabilidad con Prometheus, Loki y Grafana.
- **Scrapy Rewards:** sistema de canje de puntos por cupones ecológicos (backend en TypeScript con Prisma y frontend web). 🌐 [beneficios.scrapyapp.com](https://beneficios.scrapyapp.com)
- **Scrapy Industrial:** marketplace para la venta de materiales reciclados.
- **Panel de administración:** Next.js 15 y React 19.

### 🖨️ PrintScript: lenguaje propio y plataforma de snippets
Proyecto de Ingeniería de Sistemas en dos partes.
- **Intérprete y CLI (Kotlin):** lexer, parser, intérprete, formatter y linter de un lenguaje propio, organizados en módulos Gradle y con soporte para dos versiones del lenguaje (1.0 y 1.1). El CLI permite validar, ejecutar, formatear y analizar programas. Implementé el CLI y el intérprete para la versión 1.1 y armé los git hooks, la configuración de Gradle y la cobertura de tests.
- **Plataforma de microservicios:** servicios de snippets, permisos y lenguaje en Java/Spring, más una UI en React. Implementé casos de uso de los servicios, la integración del linter y el formatter, tests, monitoreo con New Relic y la infraestructura con Docker Compose y Nginx.

🔗 [PrintScript](https://github.com/Ingenieria-de-Sistemas-123/PrintScript) · [snippet-service](https://github.com/Ingenieria-de-Sistemas-123/snippet-service) · [language-service](https://github.com/Ingenieria-de-Sistemas-123/language-service) · [permission-service](https://github.com/Ingenieria-de-Sistemas-123/permission-service) · [printscript-ui](https://github.com/Ingenieria-de-Sistemas-123/printscript-ui) · [infra](https://github.com/Ingenieria-de-Sistemas-123/infra)

---

## 🎓 Otros proyectos
- **MicroChangas:** formo parte del equipo de dirección del proyecto (producto y coordinación del equipo).
- **ASECA Portfolio Tracker:** gestión de un portfolio de acciones con datos de SEC EDGAR, con foco en testing y aseguramiento de calidad.
- **PupResorts:** sistema full stack (Express + TypeScript y React).
- **Grieta Royale:** juego multijugador en Unity (C#).
- **Visión artificial:** proyecto en Python.

---

### 🏢 Organizaciones
[Scrapy-Austral](https://github.com/Scrapy-Austral) · [Scrapyapp](https://github.com/Scrapyapp) · [Arquinering-dev](https://github.com/Arquinering-dev) · [Ingenieria-de-Sistemas-123](https://github.com/Ingenieria-de-Sistemas-123) · [MicroChangas](https://github.com/MicroChangas)
