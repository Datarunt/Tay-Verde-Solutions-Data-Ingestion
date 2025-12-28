Purpose: prove idempotent, validated ingestion with invariants.

Data sources (brief, no essays)
Idempotency guarantee (exactly what it means here)
How to run one week + how to backfill
How invalid data is handled
Where artifacts/logs are saved

Deliverables

- NOAA ingestion script + logs
- USDA ingestion script + logs
- Incidents ingestion script + logs
- Unified run_weekly_ingest wrapper
- Schema normalization + validation (reject bad payloads)
- Backfill 8–12 weeks
- “Intentionally corrupt one run” + postmortem
- Clear statement of mold-vs-delivery invariants
