# CodePro

> Plataforma web para ofrecer servicios profesionales de desarrollo de software a medida — desde aplicaciones web y móviles hasta APIs, integraciones y consultoría técnica.

---

## Descripción general

**CodePro** es una página web corporativa diseñada para posicionar y comercializar servicios de desarrollo de software. El sitio actúa como el principal canal de adquisición de clientes: presenta el portafolio del equipo, detalla los servicios disponibles, permite solicitar cotizaciones y genera confianza mediante casos de estudio reales y testimonios verificados.

El proyecto está construido sobre Next.js, lo que permite tener frontend y backend en un único repositorio, desplegado en un solo paso a Vercel.

## Video de Presentación

https://corhuilaeduco-my.sharepoint.com/:v:/g/personal/juanninco_20182_corhuila_edu_co/IQD53iAaXh1qTp-GBhkG2KYNAWkWh40g71eQkd6zp-x1-YI?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=h1eI51

---

## Problema que resuelve

Muchos estudios y freelancers de desarrollo de software cuentan con excelente capacidad técnica pero carecen de una presencia digital profesional que transmita confianza, comunique su propuesta de valor con claridad y convierta visitantes en clientes.

**CodePro** resuelve tres fricciones concretas:

1. **Visibilidad** — Sin un sitio optimizado para SEO, los clientes potenciales no encuentran el servicio en búsquedas orgánicas.
2. **Credibilidad** — Sin portafolio, casos de estudio ni testimonios, el proceso de venta depende 100% del contacto directo y referencias.
3. **Conversión** — Sin un formulario de cotización ni seguimiento, los leads se pierden por falta de respuesta oportuna.

---

## Stack tecnológico

| Capa              | Tecnología                                         | Justificación                                                                   |
| ----------------- | -------------------------------------------------- | ------------------------------------------------------------------------------- |
| **Framework**     | [Next.js 14](https://nextjs.org) + TypeScript      | Frontend y backend en un solo proyecto, con App Router y API Routes integradas  |
| **UI**            | React                                              | Componentes reutilizables incluidos en Next.js, sin configuración extra         |
| **Estilos**       | [Tailwind CSS](https://tailwindcss.com)            | Clases utilitarias, diseño responsive-first, sin CSS custom                     |
| **API / Backend** | Next.js API Routes                                 | Rutas del servidor dentro del mismo proyecto, sin necesidad de Express separado |
| **Email**         | [Nodemailer](https://nodemailer.com)               | Envío de emails transaccionales desde las API Routes del servidor               |
| **Validación**    | [Zod](https://zod.dev)                             | Validación de datos de entrada en las rutas de la API                           |
| **Contenido**     | Markdown + archivos locales                        | Blog y portafolio en el mismo repositorio, sin CMS externo                      |
| **Analíticas**    | [Google Analytics 4](https://analytics.google.com) | Seguimiento de visitas y conversiones con una línea de código                   |
| **Despliegue**    | [Vercel](https://vercel.com)                       | Plataforma nativa de Next.js, HTTPS automático y deploy desde GitHub            |

---

## Estructura de fases / Sprints

El proyecto se organiza en **3 épicas (milestones)**, cada una compuesta por historias de usuario priorizadas:

---

### Fase 1 — Fundamentos y presencia web

**Periodo:** Mayo – Junio 2025 · `milestone/m1-fundamentos`

Establece las bases del sitio: identidad visual, arquitectura de navegación, sección hero, SEO técnico y primer despliegue en producción.

| #     | Historia de usuario                              | Labels              |
| ----- | ------------------------------------------------ | ------------------- |
| HU-01 | Diseño de identidad visual y sistema de diseño   | `design` `frontend` |
| HU-02 | Sección hero con propuesta de valor clara        | `frontend` `design` |
| HU-03 | Arquitectura de navegación y estructura de rutas | `frontend`          |
| HU-04 | Despliegue inicial en entorno de producción      | `devops`            |
| HU-05 | SEO técnico base y metadatos                     | `content` `devops`  |

---

### Fase 2 — Contenido, servicios y conversión

**Periodo:** Julio – Agosto 2025 · `milestone/m2-contenido`

Construye el núcleo comercial del sitio: catálogo de servicios, portafolio, formulario de cotización, testimonios y blog técnico.

| #     | Historia de usuario                              | Labels                        |
| ----- | ------------------------------------------------ | ----------------------------- |
| HU-06 | Página de catálogo de servicios                  | `frontend` `content`          |
| HU-07 | Portafolio de proyectos con casos de estudio     | `frontend` `content` `design` |
| HU-08 | Formulario de contacto y solicitud de cotización | `frontend` `backend`          |
| HU-09 | Sección de testimonios y reseñas de clientes     | `frontend` `content`          |
| HU-10 | Blog técnico con artículos y recursos            | `content` `frontend` `devops` |

---

### Fase 3 — Optimización, analítica y escalabilidad

**Periodo:** Septiembre – Octubre 2025 · `milestone/m3-optimizacion`

Eleva el sitio a nivel de producto: analíticas avanzadas, soporte multilenguaje, performance y automatización de marketing.

| #     | Historia de usuario                                     | Labels               |
| ----- | ------------------------------------------------------- | -------------------- |
| HU-11 | Panel de administración de contenido para el equipo     | `backend` `devops`   |
| HU-12 | Integración de analíticas y seguimiento de conversiones | `devops` `backend`   |
| HU-13 | Soporte multilenguaje español e inglés                  | `frontend` `content` |
| HU-14 | Optimización de performance y Core Web Vitals           | `frontend` `devops`  |
| HU-15 | Automatización de email marketing para leads capturados | `backend` `devops`   |

---

## Tablero de GitHub Projects

El seguimiento detallado de tareas, issues y progreso por épica está disponible en:

**[Ver tablero en GitHub Projects](https://github.com/users/juan9734/projects/2)**

> El tablero incluye vistas Kanban por fase, filtros por label y seguimiento de fechas límite por milestone.

---

## Labels del repositorio

| Label      | Descripción                                     |
| ---------- | ----------------------------------------------- |
| `frontend` | Trabajo de UI/UX, componentes React, estilos    |
| `backend`  | API Routes de Next.js, lógica de negocio, email |
| `design`   | Maquetas, identidad visual, animaciones         |
| `content`  | Textos, SEO, copywriting, Markdown              |
| `devops`   | CI/CD, despliegue en Vercel, monitoreo          |

---

## Arranque local

```bash
# Clonar el repositorio
git clone https://github.com/juan9734/code-pro.git
cd website

# Instalar dependencias
npm install

# Configurar variables de entorno
cp .env.example .env.local

# Iniciar servidor de desarrollo
npm run dev
```

El sitio estará disponible en `http://localhost:3000`.

---

## Estructura del proyecto

```
codepro/
├── public/                     # Assets estáticos (favicon, og-image)
├── app/                        # App Router de Next.js
│   ├── page.tsx                # Homepage con sección hero
│   ├── servicios/
│   │   └── page.tsx            # Catálogo de servicios
│   ├── portafolio/
│   │   └── page.tsx            # Proyectos y casos de estudio
│   ├── blog/
│   │   └── page.tsx            # Listado de artículos
│   ├── contacto/
│   │   └── page.tsx            # Formulario de cotización
│   └── api/
│       └── contact/
│           └── route.ts        # POST /api/contact — envío de email
├── components/                 # Componentes reutilizables
├── content/                    # Archivos Markdown (blog, portafolio)
├── lib/
│   └── mailer.ts               # Configuración de Nodemailer
├── .env.example
├── next.config.ts
├── tailwind.config.ts
└── tsconfig.json
```

---

## Contribución

1. Crea un branch desde `main` con el formato `hu-XX/descripcion-corta`
2. Referencia el issue correspondiente en el PR: `Closes #XX`
3. Asegúrate de que el proyecto compila sin errores antes de solicitar revisión
4. El merge a `main` requiere aprobación de al menos un revisor

---

## Licencia

Este proyecto es propiedad de **CodePro**. Todos los derechos reservados © 2025.

---

## Sprint 1 — Plan

Fecha de inicio: 18 de abril de 2026
Fecha de fin: 21 de abril de 2026

Historias de usuario en las que se trabajarán:
HU-01
HU-02
HU-03
HU-04
HU-05

Criterio de selección:
Al crear las historias de usuario se ordenaron por dependencia y por prioridad durante el desarrollo del proyecto.
