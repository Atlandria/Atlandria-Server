# atlandria-server

SaaS multi-tenant de Atlandria. Monolito modular ABP (.NET) con bounded contexts DDD: Tenancy, Registry, Knowledge, Skills, Memory, Providers, Search/RAG.

- Base de datos: Supabase (Postgres + pgvector) vía EF Core (ver ADR-0002 del meta-repo).
- Especificaciones: `.specs/` del meta-repo atlandria.

## Estado

Fase 0 — pendiente de scaffolding ABP (Fase 1 del plan).

Requisito previo: `dotnet tool install -g Volo.Abp.Studio.Cli` y resolver ADR-0002.
