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

### November 2026 - Foundation
- Create project workspace and repository
- Read foundational papers and standards
- Define terminology
- Define survey methodology
- Identify candidate FOSS systems
- Agree inclusion/exclusion criteria
- Draft research questions

### December 2026 - Selection and benchmark design
- Complete candidate-system survey
- Select final PoC systems
- Freeze system-selection rationale
- Define benchmark task categories
- Define common datasets/tools
- Define metrics and success criteria
- Design common infrastructure

### January 2027 - Implementation
- Build one PoC per selected system
- Containerize systems where practical
- Integrate local/self-hosted model serving
- Connect common benchmark tools
- Add logging/tracing
- Run pilot benchmark

### February 2027 - Evaluation
- Run final benchmark
- Run security tests
- Collect performance/resource metrics
- Analyse failures and limitations
- Compare systems
- Prepare figures/tables

### March 2027 - Finalization if needed
- Repeat weak experiments
- Complete report
- Prepare demo/UI
- Final presentation

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
