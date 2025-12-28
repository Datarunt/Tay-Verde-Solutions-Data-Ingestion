## System context

This repository is part of a larger **reliability-first industrial IoT system**.
The system is intentionally split into four focused, frozen repositories.

**Explore the full system:**
1. [Edge-reliability](https://github.com/Datarunt/Tay-Verde-Solutions-Edge-Reliability)
2. [Data-ingestion](https://github.com/Datarunt/Tay-Verde-Solutions-Data-Ingestion)
3. [Control-plane](https://github.com/yourusername/risk-control-plane-airflow)
4. [ML-system](https://github.com/Datarunt/Tay-Verde-Solutions-ML-System)

You are currently viewing: **<Edge-Reliability>**

Purpose: prove idempotent, validated ingestion with invariants.

- Data sources (brief, no essays)
- Idempotency guarantee (exactly what it means here)
- How to run one week + how to backfill
- How invalid data is handled
- Where artifacts/logs are saved

Deliverables

- NOAA ingestion script + logs
- USDA ingestion script + logs
- Incidents ingestion script + logs
- Unified run_weekly_ingest wrapper
- Schema normalization + validation (reject bad payloads)
- Backfill 8–12 weeks
- “Intentionally corrupt one run” + postmortem
- Clear statement of mold-vs-delivery invariants
