# System Survey - Inclusion and Exclusion Criteria

The final PoC systems must be selected using explicit criteria rather than personal preference.

## Mandatory inclusion criteria

A candidate should:
- have an identifiable open-source/FOSS software license
- support self-hosted/local/on-premise deployment of the agent system
- provide genuine agentic behavior such as tool use, planning, multi-step execution, or orchestration
- support integration with a local/self-hosted model, or clearly document any limitation
- have enough documentation to reproduce a basic deployment
- be runnable on infrastructure reasonably available to the team

## Exclusion criteria

Exclude a candidate if:
- it is primarily a cloud-only SaaS product
- no usable source code/license is available
- it is only a chatbot UI without meaningful agent/tool functionality
- it cannot be reproduced from available documentation
- the project is abandoned to the point that a current setup is not practical
- it requires inaccessible proprietary dependencies for core operation

## Secondary comparison parameters

Record these for every candidate:
- license
- project type: framework/platform/application/UI
- programming language
- self-hosting method
- Docker support
- local model support
- supported model servers
- tool calling
- API integration
- MCP support
- memory
- persistent memory
- multi-agent support
- RAG/document support
- database integration
- code execution
- sandbox/isolation support
- authentication/authorization options
- logging/tracing
- observability
- offline capability
- extensibility/custom tools
- documentation quality
- release/commit activity
- community/adoption indicators
- CPU/RAM/GPU requirements
- Windows/Linux support
- known security controls
- known limitations

## Selection principle

Do not simply choose the five highest-scoring systems if they are architecturally identical. Prefer a representative set covering meaningfully different system types where possible.

Examples of categories:
- developer-oriented orchestration framework
- multi-agent framework
- lightweight agent framework
- autonomous agent platform
- workflow/UI-oriented agent platform

## Decision record

The final selection must document:
1. candidates considered
2. candidates excluded and why
3. systems remaining after mandatory filters
4. rationale for the final representative set
