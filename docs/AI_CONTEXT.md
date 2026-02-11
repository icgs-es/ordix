# ORDIX CORE — AI CONTEXT (pegable)

## Objetivo
Construir un SaaS en Python + Django. Prioridad: producto funcional y usable a diario (no rediseño global).

## Alcance MVP (sí entra)
- Login/permisos básicos
- Agenda/Tareas (“Mi jornada”)
- Archivos (nivel SaaS: multi-upload real, carpetas, UX pro)
- Estabilidad (sin 500), logs útiles
- Backups/restauración probada (infra ya controlada)

## Fuera de alcance (no entra ahora)
- Facturación/ERP
- CRM avanzado
- Permisos ultra-granulares
- Integraciones infinitas
- Cambios grandes de infraestructura

## Stack
- Backend: Django + PostgreSQL
- Deploy: AWS (controlado)
- Repo: GitHub

## Reglas de trabajo
- No tocar infraestructura salvo que el issue lo pida explícitamente.
- Cambios pequeños y mergeables (1–4h).
- Siempre añadir plan de pruebas y checklist de PR.

## Estado actual (resumen)
- El módulo Archivos funciona pero NO es profesional (multi-upload inconsistente, no carpetas, UX desordenada).
- Objetivo: llevar Archivos a nivel SaaS profesional.

## Convenciones (rellenar si aplica)
- Apps Django principales: (pon aquí: core, agenda, files, etc.)
- Rutas importantes:
- Estilo UI: tema claro pro (sin rediseño global ahora)
