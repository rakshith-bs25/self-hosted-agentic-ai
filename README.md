# Self-Hosted FOSS Agentic AI

Master's IT Security team project investigating free and open-source agentic AI systems that can be self-hosted locally or on-premise.

## Project goals

1. Review academic and standards literature on agentic AI, self-hosting, security, and digital sovereignty.
2. Conduct a structured survey of available FOSS agentic AI systems.
3. Define transparent inclusion/exclusion and selection criteria.
4. Select representative systems for proof-of-concept implementations.
5. Evaluate the selected systems in a common benchmark environment.
6. Compare functionality, reliability, performance, resource use, security, deployment effort, and reproducibility.
7. Build a reusable evaluation platform that may later support enterprise/laboratory AI use cases.

## Repository structure

- `docs/` - project plan, research questions, roles, decisions, architecture
- `literature/` - literature-review method and paper notes
- `survey/` - candidate-system survey and selection methodology
- `benchmark/` - benchmark specification, tasks, datasets, evaluators
- `infrastructure/` - Docker, model serving, databases, monitoring
- `pocs/` - one proof-of-concept implementation per selected system/student
- `results/` - raw and processed experiment results
- `report/` - report-related material
- `ui/` - optional evaluation dashboard/frontend/backend

## Current status

**Phase 1: Project setup, literature review, and FOSS system survey.**

Do not select the final PoC systems before the survey and selection criteria are agreed by the team.

## Security

Never commit secrets, API keys, passwords, private company data, production datasets, or `.env` files.
