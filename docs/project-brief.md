# Project Brief (from supervisor)

Topic 5: Self-hosting FOSS Agentic AI
Supervisor: Christian Krätzer
Intended team size: 2-4 students (this team: 5, approved by supervisor)

> Note: the same topic was also assigned to a second team.

## Introduction / aim (as given in the brief)

- Agentic AI is a new driver in many security considerations in IT security research and application.
- The vast majority of existing solutions is based on online systems provided by a few big tech companies. Their usage creates a wide range of issues with regard to **security**, **resource efficiency** and **digital sovereignty**.

## Required procedures (as given in the brief)

1. Familiarization with the given literature, especially NIST (USA) and BSI (Germany) sources on AI and agentic AI, plus [Gohil2026] and [Sapkota2026]. Sources: see `literature/sources.md`.
2. Provide a survey on free and open-source software (FOSS) agentic AI that can be self-hosted (locally / on premise).
3. Illustrate the self-hosting of FOSS agentic AI with proof-of-concept setups (**at least one per student**).

## Expected results (as given in the brief)

- Final presentation
- Scientific report, including:
  - overview of tools used
  - code / implementations, incl. documentation of the parameterization used
  - log, test and result data

## Our interpretation (to be confirmed with the supervisor)

- The three evaluation lenses for every surveyed system and every PoC are the ones named in the brief: security, resource efficiency, digital sovereignty.
- As this is an IT security project, each PoC should include a security evaluation, not only a working setup.
- All PoCs follow one common evaluation pipeline so results are comparable (see `docs/project-plan.md` and `benchmark/`).

## Milestones

| Date | Milestone |
|---|---|
| 24 Nov 2026 | Kickoff presentation to supervisor: understanding of the topic, approach, timeline, tools, work distribution |
| 18 Jan 2027 | Final presentation |
| tbd | Report submission |

## Open questions for the supervisor

1. Hardware: is a university server / GPU machine available, or do we self-host on our own machines?
2. How strict is "FOSS" for the model layer? (a) fully open models (weights, data, code), (b) open-weight models under an OSI license such as Apache 2.0 / MIT, (c) open-weight models under custom licenses with usage conditions.
3. Is a security evaluation expected for every PoC?
4. Should the PoCs cover different types of agentic systems (e.g. single-agent, multi-agent, coding agent)?
5. Which Sapkota paper is meant exactly? Is it acceptable to use NIST AI 100-2 E2025 instead of / in addition to E2023?
