# Common Benchmark

## What this is

The common benchmark is a shared set of tasks, data, tools, environment constraints, and metrics used to evaluate all selected PoC systems fairly.

It does NOT mean putting all agents into one Python file.

Each framework/system can have its own implementation, but all should face equivalent test conditions where technically possible.

## Principle

Same task + same data + same available tools + same model where possible + same success criteria = meaningful comparison.

## Initial benchmark areas

1. Document retrieval/use
2. Database/tool use
3. Multi-step reasoning and tool orchestration
4. Failure recovery
5. Security and permission handling
6. Performance/resource use

## Example task

Question:
"Which laboratory devices have calibration due within the next 30 days, and what maintenance instructions apply?"

Possible workflow:
1. query PostgreSQL
2. retrieve relevant documentation
3. combine results
4. return structured answer

## Metrics to consider

- task success
- answer correctness
- tool-selection correctness
- tool-argument correctness
- repeated-run reliability
- latency
- model calls
- tool calls
- CPU
- RAM
- GPU/VRAM
- external network dependency
- security-policy violations
- recovery after tool failure

## Benchmark versioning

When the final benchmark is defined, freeze:
- hardware
- OS
- model
- model version
- quantization
- temperature
- maximum steps
- timeout
- task set
- tool set
- expected outputs
- scoring rules

Store this in a versioned benchmark specification, e.g. Benchmark v1.0.
