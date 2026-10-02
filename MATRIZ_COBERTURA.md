# Matriz de cobertura — DataGov Local

Esta matriz conecta cada requerimiento explícito del formulario con una implementación, prototipo o pendiente verificable.

| Requerimiento | Estado | Evidencia / ubicación |
|---|---|---|
| 100% local/on-premise sin APIs externas | **Documentado** | arquitectura.html + seguridad.html |
| Python, FastAPI, LangGraph, Ollama, Qdrant y Docling | **Documentado** | Arquitectura y roadmap |
| Oracle 19c, Azure DevOps, archivos y Git | **Documentado** | Fuentes e integraciones |
| Supervisor + agentes especializados | **Implementado en diseño** | agentes.html |
| RAG híbrido: embeddings, BM25, filtros y reranking | **Documentado** | arquitectura.html |
| ERD, flujos, arquitectura, linaje, DDL y documentos | **Implementado en UX** | Workbench + documentación |
| Trazabilidad y separación hechos/recomendaciones | **Implementado en contenido** | Seguridad + Workbench |
| RBAC, ACL, auditoría, aprobación, read-only, Docker, secretos y Git | **Documentado** | seguridad.html |
| VS Code, CLI y web | **Documentado** | Arquitectura |
| MVP por fases | **Implementado** | roadmap.html |
| Funcionalidad ejecutable real | **Pendiente de backend** | No se simula como implementada; requiere proyecto de software separado |

## Criterio de estados
- **Implementado:** existe una página, componente o contenido específico en el prototipo.
- **Prototipo / preparado:** la experiencia está diseñada, pero requiere backend, datos, credenciales o validación.
- **Documentado:** la arquitectura y controles están explicados, no desplegados.
- **Pendiente / no verificable:** falta información del alumno o la referencia no pudo confirmarse.
