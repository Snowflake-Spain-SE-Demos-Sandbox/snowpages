# Snowflake — Aceleradores IA/ML por Industria

Colección de **guías detalladas** y **Cortex Code Prompts** listos para desplegar, organizados por vertical de industria. Cada caso de uso incluye datos sintéticos, modelos ML/NLP y dashboards Streamlit interactivos — todo 100% nativo en Snowflake.

🔗 **[Ver sitio web](https://snowflake-spain-se-demos-sandbox.github.io/aimlcases/)**

---

## Ficheros Principales

| Fichero | Descripción |
|---|---|
| `index.html` | Página principal — catálogo de industrias con buscador |
| `index_en.html` | Versión en inglés de la página principal |
| `manual.html` | Guía paso a paso para usar Cortex Code en Snowsight |
| `manual_en.html` | Versión en inglés del manual |
| `bug-white.png` | Logo Snowflake |
| `README.md` | Este fichero |

---

## `index.html` — Página Principal

Portal de búsqueda y acceso a todos los aceleradores IA/ML por industria. Incluye:

- **Buscador global** de casos de uso por nombre o descripción
- **Tarjetas por industria** con número de casos de uso y enlace directo
- **Versión en inglés** (`index_en.html`) con el mismo contenido

---

## `manual.html` — Guía de Uso de Cortex Code

Manual completo en **12 secciones** para desplegar cualquier caso de uso con Cortex Code en Snowsight:

| # | Sección |
|---|---|
| 1 | ¿Qué es Cortex Code? |
| 2 | Requisitos Previos |
| 3 | Abrir Cortex Code en Snowsight |
| 4 | Añadir la Skill de Best-Practices a Cortex Code |
| 5 | Flujo de Trabajo con los Prompts |
| 6 | Ejecutar un Caso de Uso Paso a Paso |
| 7 | Revisar y Validar el Código Generado |
| 8 | Desplegar Dashboards Streamlit |
| 9 | Automatizar con Tasks y Pipelines |
| 10 | Comprobar Gasto Utilizado |
| 11 | Consejos y Buenas Prácticas |
| 12 | Preguntas Frecuentes |

---

## Industrias — Resumen

| Industria | Fichero | UCs | Categorías |
|---|---|---|---|
| **Farmacéutica** | `farmaceutica.html` | 27 | Machine Learning · IA y Lenguaje Natural · Journey del Paciente |
| **Seguros** | `seguros.html` | 36 | Detección de Fraude · Riesgo y Suscripción · IA y Lenguaje Natural · Gestión de Siniestros · Call Center IA · Asistentes IA · Comercial y Red · Operaciones · Pricing |
| **Banca** | `banca.html` | 20 | Riesgo y Compliance · Cliente y Negocio · Operaciones y Mercados · Inteligencia Avanzada |
| **Energía y Utilities** | `energia.html` | 20 | Generación Renovable · Red y Smart Grid · Experiencia de Cliente · Operaciones y Eficiencia · Seguridad y Cumplimiento |
| **Gestión del Agua** | `agua.html` | 10 | Operación de Planta · Calidad del Agua · Red de Distribución · Experiencia de Cliente |
| **Retail y E-Commerce** | `retail.html` | 20 | Personalización y CX · Pricing & Revenue · Supply Chain · Marketing & Loyalty · Fraude y Seguridad |
| **Salud y Hospitales** | `salud.html` | 20 | Atención al Paciente · Datos Clínicos · Operaciones · Crónicos · Seguridad |
| **Educación** | `educacion.html` | 20 | Experiencia Estudiante · Gestión Académica · Admisiones · Investigación · Operaciones |
| **Telecomunicaciones** | `telecom.html` | 20 | Red y Conectividad · Experiencia de Cliente · Operaciones y Eficiencia · Monetización y Ofertas · Seguridad y Cumplimiento |
| **Logística y Transporte** | `logistica.html` | 20 | Rutas y Última Milla · Almacén y Fulfillment · Flota y Mantenimiento · Demanda y Planificación · Seguridad y Cumplimiento |
| **Sector Público** | `sector_publico.html` | 20 | Experiencia Ciudadana · Políticas Públicas · Fraude y Control · Eficiencia Administrativa · Seguridad y Smart Cities |
| **Medios Audiovisuales** | `medios.html` | 20 | Contenido y Producción · Audiencia y Engagement · Publicidad y Monetización · Distribución y Plataformas · Seguridad y Derechos |
| **Hospitality** | `hospitality.html` | 20 | Revenue & Pricing · Experiencia del Huésped · Operaciones · Distribución B2B · Fraude y Seguridad |
| **Manufactura** | `manufactura.html` | 15 | Calidad y Producción · Mantenimiento Predictivo · Cadena de Suministro · Operaciones IA |

> **Total: ~278 casos de uso** · Versiones en inglés disponibles para algunas industrias (`_en.html`)

---

## Estructura de Ficheros

```
├── index.html / index_en.html          # Catálogo principal de industrias
├── manual.html / manual_en.html        # Guía de uso de Cortex Code (12 secciones)
├── farmaceutica.html / _en.html        # Farmacéutica (27 UCs)
├── seguros.html / _en.html             # Seguros (36 UCs)
├── banca.html / _en.html               # Banca (20 UCs)
├── energia.html / _en.html             # Energía y Utilities (20 UCs)
├── agua.html / _en.html                # Gestión del Agua (10 UCs)
├── retail.html                         # Retail y E-Commerce (20 UCs)
├── salud.html                          # Salud y Hospitales (20 UCs)
├── educacion.html / _en.html           # Educación (20 UCs)
├── telecom.html                        # Telecomunicaciones (20 UCs)
├── logistica.html                      # Logística y Transporte (20 UCs)
├── sector_publico.html                 # Sector Público (20 UCs)
├── medios.html                         # Medios Audiovisuales (20 UCs)
├── hospitality.html / _en.html         # Hospitality (20 UCs)
├── manufactura.html                    # Manufactura (15 UCs)
├── bug-white.png                       # Logo Snowflake
└── README.md
```

---

## Cómo Usar

1. **Abrir** la web (`index.html`) y seleccionar una industria
2. **Leer** el `manual.html` para entender el flujo de trabajo con Cortex Code
3. **Explorar** los casos de uso y abrir la **Guía** para entender el contexto y los datos
4. **Copiar** los **Cortex Code Prompts** y ejecutarlos secuencialmente en Cortex Code (Snowsight)
5. **Personalizar** reemplazando los datos sintéticos con tus propios datos

---

## Requisitos

- Cuenta de Snowflake con acceso a Cortex AI/ML:
  - `SNOWFLAKE.ML.CLASSIFICATION` — modelos de clasificación
  - `SNOWFLAKE.ML.FORECAST` — forecasting de series temporales
  - `SNOWFLAKE.CORTEX.COMPLETE` — LLM inference (mistral-large2, llama3.1-70b)
  - `SNOWFLAKE.CORTEX.SENTIMENT` — análisis de sentimiento
  - `SNOWFLAKE.CORTEX.TRANSLATE` — traducción multi-idioma
  - `SNOWFLAKE.CORTEX.SUMMARIZE` / `CLASSIFY_TEXT` — resumen y clasificación
  - `AI_EXTRACT` — extracción estructurada de texto libre
  - Cortex Search Service — búsqueda semántica RAG
  - Cortex Analyst — lenguaje natural a SQL
- Warehouse `SMALL` o superior (auto-suspend 60s recomendado)
- Rol con permisos `CREATE DATABASE`
- Acceso a **Cortex Code** en Snowsight
- Skill `/best-practices` instalada en Cortex Code (descargable desde `manual.html`)

---

## Stack Tecnológico

- **Snowflake Cortex AI** — LLM inference, sentiment, summarize, translate, classify
- **Snowflake Cortex ML** — AutoML classification y forecasting
- **Snowflake Cortex Search** — RAG pipelines y búsqueda semántica
- **Snowflake Cortex Analyst** — lenguaje natural a SQL con capa semántica
- **Snowflake Cortex Code** — prompts guiados paso a paso con skills
- **Streamlit in Snowflake** — dashboards interactivos
- **GitHub Pages** — hosting estático del catálogo web

---

Desarrollado con Snowflake Cortex AI + Cortex Code + Streamlit
