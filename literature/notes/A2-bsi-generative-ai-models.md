# BSI: Generative AI Models – Opportunities and Risks for Industry and Authorities

Reader: Rakshith | Date read: 21 Nov 2026 | Source # in `sources.md`: A2

Source: BSI (2025), version 2.0, 17 Jan 2025.
PDF (EN): https://www.bsi.bund.de/SharedDocs/Downloads/EN/BSI/KI/Generative_AI_Models.pdf
Also on arXiv: https://arxiv.org/abs/2406.04734

Scope note: the brief points to the BSI AI topic page. This publication is the BSI's main document on generative AI / LLM security linked from that page, so it is used as the A2 source.

## Key ideas

- Aimed at companies and authorities that plan to use generative AI; meant as a basis for a systematic risk analysis, not as a complete checklist.
- Risks are grouped by origin: proper use (R1–R9), misuse (R10–R16), and attacks on the model (R17–R28). Attacks are split into poisoning, privacy (information extraction) and evasion attacks.
- R1 (dependency on the provider) and R2 (lack of confidentiality of inputs) describe the main problems of cloud-hosted models: no control over availability, development or security mechanisms, and possible access to or reuse of user data by the provider.
- LLMs do not separate instructions from data (R3). If an application can act autonomously, text from third-party sources can trigger unwanted actions (e.g. sending or deleting emails).
- Risks especially relevant for agents: remote code execution when generated code is executed (R16), poisoning of RAG knowledge bases (R18), extraction of system prompts / chat history / knowledge base (R25) and indirect prompt injection via websites, emails or documents (R28).
- Self-hosting adds operator-side risks: manipulated weights or serialised model files from public repositories (R19) and reconstruction of text from stored embeddings in vector databases (R23).
- Countermeasures are ordered along the model lifecycle and addressed to users, developers and operators. Classic IT security (access control, isolation, signatures) plus IT-Grundschutz, C5 and AIC4 are recommended alongside.
- Residual risks remain even if all countermeasures are applied.

## What we can reuse in our project

- **Motivation for self-hosting:** R1 and R2 give an official German-authority argument for why organisations would self-host (control, confidentiality, digital sovereignty).
- **Security evaluation structure:** the R1–R28 grouping can be used to classify the threats we test, and to map our tests to a citable reference (alongside NIST).
- **Concrete test ideas for agents:** indirect prompt injection with a poisoned document (R28), RAG knowledge poisoning (R18), system prompt / knowledge base extraction (R25), unsafe execution of generated code (R16).
- **Survey / selection criteria:** M1 lists model-selection questions (supply chain, evaluation, versioning, residual risks, on-premises compute and storage needs) that can feed our inclusion criteria.
- **Simple self-hosting checks:** model file format (prefer Safetensors over Pickle, M5), integrity of downloaded models (R19), protection of vector stores (R23).

## Systems / tools mentioned

- No specific agentic AI systems or frameworks are named.
- Formats mentioned: Pickle (avoid), Safetensors, MessagePack.
- Related BSI catalogues: IT-Grundschutz, C5, AIC4.

## Limitations of this source

- Covers generative AI in general; agents and tool use appear only inside individual risks, not as a separate topic.
- Describes risks and countermeasures but gives no test methods, metrics or benchmarks.
- Explicitly not exhaustive; risk relevance depends on the use case.
- The countermeasures after M10 and the mapping chapter (ch. 6) were only skimmed.

## Open questions for the supervisor

- Should our security tests be mapped to the BSI risk IDs (e.g. R28) in addition to the NIST taxonomy?
