# DB-ReGen
A self-healing data &amp; schema corruption repair orchestrated by LLM + Bash tools.

Self-Healing Databases via MCP-Mediated Bash + SQL Repair Workflows
Novelty Pivot: Moves beyond tuning (CHESS, DB-GPT) to self-healing data & schema corruption repair orchestrated by LLM + Bash tools.
Concept:
Detects corruption or integrity violations (checksum mismatch, FK errors, missing indexes).
LLM plans multi-step recovery using MCP tools: pg_dump, sed, data diff, checksum verification, partial reload.
Generates both the SQL repair script and the Bash job pipeline to apply it safely.
Includes rollback plan and integrity validation post-repair.
Research Contribution: Defines LLM-orchestrated self-healing for relational systems, integrating tool calls, verification, and rollback—all absent from existing literature.
