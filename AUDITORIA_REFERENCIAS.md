# Auditoría de fuente — DataGov Local

## Registro original
- **Alumno:** Juan Francisco Forasassi Frías
- **Correo:** forasassi@gmail.com
- **Tipo:** aplicacion_movil
- **Estilo solicitado:** Tecnológico
- **Sensación solicitada:** La web debería transmitir una sensación de IA corporativa seria, segura y altamente competente, no de “chat experimental”.
- **Descripción del negocio:** Es una plataforma de **IA agéntica local especializada en Ingeniería y Gobierno de Datos**, diseñada para trabajar de forma segura dentro de la red corporativa. La solución analiza políticas, procedimientos, requerimientos, Azure DevOps, documentación y metadatos de bases de datos para ayudar a diseñar modelos de datos, generar SQL, diagramas, Excel, presentaciones y documentación técnica. Todo funciona con modelos de IA locales, manteniendo la información sensible dentro de la organización y ofreciendo trazabilidad sobre las fuentes y decisiones utilizadas.
- **Detalles técnicos:** Quiero construir una plataforma **RAG Agéntica 100% local/on-premise para Ingeniería y Gobierno de Datos**, sin enviar información a APIs externas.

La solución debe usar preferiblemente **Python + FastAPI + LangGraph + Ollama + Qdrant + Docling**, con integración a **Oracle 19c, Azure DevOps, archivos locales y Git**.

Debe poder leer y analizar:
- políticas;
- procedimientos;
- normativas;
- solicitudes;
- documentación;
- backlog;
- Epics, Features, HU y Tasks de Azure DevOps;
- modelos de datos existentes;
- metadatos de Oracle.

Quiero un **Supervisor Agent** que coordine agentes especializados para:
- RAG/Governance;
- análisis de requerimientos;
- descubrimiento de datos;
- modelado conceptual, lógico y físico;
- generación de SQL Oracle;
- calidad de datos;
- revisión de arquitectura;
- generación de artefactos y diagramas.

El RAG debe ser **híbrido**, combinando embeddings, búsqueda lexical/BM25, filtros por metadata y reranking local.

El sistema debe generar localmente:
- modelos ER;
- diagramas de flujo;
- diagramas de arquitectura;
- linaje;
- DDL Oracle 19c;
- Excel;
- PowerPoint;
- Word/PDF;
- Markdown;
- imágenes/infografías mediante ComfyUI local.

Todo resultado debe mantener trazabilidad hacia las fuentes utilizadas y diferenciar entre requerimientos, políticas, hechos, evidencia y recomendaciones de la IA.

Debe incluir:
- RBAC;
- ACL documental;
- auditoría;
- aprobación humana para acciones críticas;
- acceso Oracle preferiblemente read-only;
- aislamiento mediante Docker;
- bloqueo de salida a Internet para componentes sensibles;
- secretos fuera del código;
- versionamiento de modelos, SQL y diagramas mediante Git.

Quiero usarlo desde **VS Code, CLI y una interfaz web interna**.

Caso de uso esperado:

“Analiza esta solicitud, revisa políticas y procedimientos, consulta Azure DevOps, busca estructuras similares en Oracle, diseña el modelo de datos, valida que cumpla los estándares y genera el DDL, ERD, diccionario Excel, documentación y presentación ejecutiva.”

Diseña primero la arquitectura, componentes, agentes, seguridad, estructura del repositorio y roadmap. Luego implementa un MVP funcional por fases, comenzando por:

**Ollama + Qdrant + Docling + FastAPI + LangGraph + RAG local + carga de documentos + generación de modelo ER y DDL Oracle.**

No simules funcionalidades. Todo lo implementado debe poder ejecutarse y probarse localmente.

## Logotipo, imágenes y archivos
El Excel no contiene imágenes, archivos incrustados, dibujos, relaciones de hipervínculos ni logotipos. El logotipo, favicon, portada social e ilustraciones de este prototipo son **originales y provisionales**. Los logos y fotografías de las páginas de referencia no se copiaron porque pertenecen a terceros y no identifican al alumno.

## Auditoría de referencias
| Referencia | Estado | Hallazgo |
|---|---|---|
| `AnythingLLM` | verificado | Se verificó el sitio oficial; referencia de IA local y privada. |
| `Dify` | verificado | Se verificó el sitio oficial; referencia de workflows agénticos listos para producción. |
| `Open WebUI` | verificado | Se verificó el sitio oficial; referencia de plataforma de IA autoalojada. |

## Supuestos explícitos
- DataGov Local es un nombre conceptual; no se proporcionó marca ni logo.
- El sitio documenta arquitectura y experiencia, no afirma que el backend ya esté implementado.
- Los indicadores, consultas y artefactos de ejemplo son sintéticos.

## Arquitectura entregada
- `index.html` — **Inicio** (home)
- `arquitectura.html` — **Arquitectura** (architecture)
- `agentes.html` — **Agentes** (services)
- `seguridad.html` — **Seguridad** (services)
- `workbench.html` — **Workbench** (dashboard)
- `roadmap.html` — **Roadmap** (timeline)
- `documentacion.html` — **Documentación** (library)
- `privacidad.html` — política base para adaptar
- `accesibilidad.html` — declaración de accesibilidad
- `404.html` — página de error no indexable
- `robots.txt`, `sitemap.xml`, `sitemap.template.xml`, `llms.txt`, `knowledge.json`, `manifest.webmanifest`

## Integraciones no simuladas como reales
La interfaz puede demostrar búsquedas, dashboards, formularios, catálogos, chat o calculadoras; no se conectaron pagos, autenticación, bases de datos, WhatsApp, CRM, LMS, IAM, Oracle ni modelos de IA porque el registro no incluye credenciales, infraestructura ni reglas operativas aprobadas.
