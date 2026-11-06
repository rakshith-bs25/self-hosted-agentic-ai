# Architecture Notes

Architecture diagrams and editable sources should live here.

Recommended files later:
- overall-architecture.drawio
- overall-architecture.png
- benchmark-architecture.drawio
- benchmark-architecture.png
- model-serving-architecture.drawio
- model-serving-architecture.png

## Initial target architecture (proposal, open for team discussion)

User / Evaluation UI
-> Evaluation backend
-> Benchmark orchestrator
-> Common agent adapter/interface
-> Selected agent framework/system
-> Self-hosted model server
-> Local/open model
-> Controlled tools

Controlled tools may include:
- database
- local documents / retrieval
- test REST API
- calculator
- controlled file operations

## Important design principle

The benchmark/evaluation platform should be reusable so that future systems or models can be plugged in without redesigning the entire project.
