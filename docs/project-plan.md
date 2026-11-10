# Project Plan

## Project
Self-Hosting FOSS Agentic AI

## Team
Five students. Each student should own one proof-of-concept unless the supervisor defines a different interpretation.

## Overall workflow

1. Literature review
2. Structured survey of FOSS agentic AI systems
3. Define inclusion/exclusion criteria
4. Select representative systems
5. Design a common benchmark
6. Build reproducible PoCs
7. Run common evaluation
8. Perform security evaluation
9. Analyse results
10. Write report and prepare demo/presentation

## Target timeline

### 10 – 24 Nov 2026 - Foundation
- Create project workspace and repository
- Read required sources (brief) and summarize them
- Define terminology
- Define survey methodology and inclusion/exclusion criteria
- Start candidate FOSS system list
- Draft research questions
- Prepare and hold first presentation (24 Nov)

### 25 Nov – 7 Dec 2026 - Survey and selection
- Complete candidate-system survey
- Select final PoC systems and freeze selection rationale
- Choose shared model and runtime (depends on available hardware)
- Define benchmark tasks, metrics and success criteria
- Define security test set (based on NIST/BSI)
- Set up common infrastructure

### 8 – 21 Dec 2026 - Implementation
- Build one PoC per selected system
- Containerize systems where practical
- Connect to shared self-hosted model serving
- Add logging/tracing
- Run pilot benchmark

### 22 Dec 2026 – 4 Jan 2027 - Holiday buffer
- Catch up on delayed PoCs (reduced availability expected)

### 5 – 11 Jan 2027 - Evaluation and final presentation prep
- Run final benchmark and security tests
- Collect performance/resource metrics
- Compare systems, prepare figures/tables
- Prepare final presentation, dry run

### 12 Jan 2027 - Final presentation

### 13 Jan – mid-March 2027 - Analysis and report
- Repeat weak or incomplete experiments
- Deepen failure and security analysis
- Write and finalize the scientific report (Overleaf)
- Submit final report (mid-March)


## Core engineering principle

The project should produce reusable, reproducible artifacts rather than five disconnected demos.

## Definition of done

A selected system is not considered complete until:
- setup is documented
- exact versions are recorded
- deployment is reproducible
- it can execute the agreed benchmark tasks
- logs/results are stored
- limitations are documented
