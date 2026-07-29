# John Wantz Jr.

### AI Systems Architect · Applied AI Platform Lead · Founder of [TARX](https://tarx.com)

I design and ship controlled AI systems across local devices, customer-managed
infrastructure, cloud services, and enterprise workflows. My work connects
agent architecture, model orchestration, retrieval, privacy, evaluation,
governance, product definition, and human-centered interaction.

[TARX](https://tarx.com) ·
[Download](https://tarx.com/download) ·
[Documentation](https://docs.tarx.com) ·
[Portfolio](https://www.johnwantz.com/portfolio) ·
[LinkedIn](https://www.linkedin.com/in/johntwantz/)

## Building TARX

TARX is a local-first AI runtime for work: **Computer by default,
Supercomputer by permission.**

It provides the operating layer around models and agents: persistent context,
private memory, approved capabilities, tool execution, policy, human approval,
model routing, and evidence. The public product entry is **TARX Computer**—not
a marketing chat wrapper and not silent cloud escalation.

```mermaid
flowchart LR
    U["Person or enterprise workflow"] --> D["TARX Desktop"]
    D --> R["Governed runtime contract"]
    R --> L["Local Computer"]
    R --> P["Private infrastructure"]
    R --> C["Approved cloud models"]
    R --> E["Evidence, approvals, and audit"]
```

The public Apple Silicon beta includes signed and notarized releases,
installation verification, a local runtime bridge, security documentation, and
system-integrity checks.

### Public proofs (read these first)

1. [TARX CLI](https://github.com/tarx-ai/tarx-cli) — `tarx route check local`,
   fail-closed remote preflight, and multi-host MCP install fixtures
2. [Governed Agent Contracts](https://github.com/tarx-ai/governed-agent-contracts)
   — portable proposal → decision → result → evidence with executable invariants
3. [Palantir AIP × Local-First](https://github.com/wantzjt/palantir-aip-local-first)
   — enterprise policy routing mapped to TARX Computer / private / deny
4. [TARX Desktop](https://github.com/tarx-ai/tarx-desktop) — Apple Silicon beta,
   Computer-canonical entry, signed releases

## Upstream systems work (inputs into TARX)

Upstream contributions matter only when they become product proof:

- **Inference preflight:** [NVIDIA NemoClaw Community #72](https://github.com/NVIDIA/nemoclaw-community/pull/72)
  → shipped as [TARX CLI route check](https://github.com/tarx-ai/tarx-cli/pull/2)
- **MCP host adapters:** [fixture corpus](https://github.com/tarx-ai/tarx-cli/pull/3)
  → evidence on [SEP-2633](https://github.com/modelcontextprotocol/modelcontextprotocol/pull/2633#issuecomment-5109652384)

NVIDIA community work is supporting systems rigor—not the product identity.

## Featured architecture: Palantir AIP × local-first AI

[Palantir AIP Local-First](https://github.com/wantzjt/palantir-aip-local-first)
is my independent, runnable reference architecture for AI systems that cross
governed enterprise workflows, sensitive local execution, and intermittent
connectivity. It is **not affiliated with or endorsed by Palantir**.

It demonstrates classification-aware policy routing, an enforceable local
inference boundary, idempotent offline reconciliation, resilient ontology
subscription patterns, structured decision evidence, and a bridge into TARX
governed action contracts (proposal / decision / result). Synthetic data only;
OSDK stays behind a clean adapter seam.

- [Read the architecture](https://github.com/wantzjt/palantir-aip-local-first/blob/main/docs/architecture.md)
- [Read the case study](https://github.com/wantzjt/palantir-aip-local-first/blob/main/docs/case-study.md)
- [Review the production-readiness checklist](https://github.com/wantzjt/palantir-aip-local-first/blob/main/docs/palantir-readiness.md)
- [Inspect the tests](https://github.com/wantzjt/palantir-aip-local-first/tree/main/test)

This is a community project and is not affiliated with or endorsed by Palantir
Technologies.

## Current focus

- Governed agents, permissions, approvals, and evidence-backed actions
- Local and private AI deployment
- Palantir-oriented enterprise AI architecture and OSDK integration boundaries
- Enterprise search, RAG, retrieval, and source grounding
- Model routing, memory, persistent context, and tool use
- Evaluation systems, acceptance criteria, QA, and release validation
- AI product and experience patterns for complex, regulated workflows
- Architecture-first implementation with AI-native engineering workflows

## Enterprise systems experience

My work spans AI and digital systems at LexisNexis, State Farm, Charles Schwab,
Target, AT&T, and venture-backed startups. I have translated legal research,
insurance support, financial advice, marketplace, identity, voice, and
enterprise-search workflows into product architecture, system requirements,
governance controls, and launch paths.

## Selected technical proof

- [Palantir AIP × local-first reference architecture](https://github.com/wantzjt/palantir-aip-local-first)
- [TARX Desktop public releases](https://github.com/tarx-ai/tarx-desktop/releases)
- [TARX system integrity](https://github.com/tarx-ai/tarx-desktop/blob/main/docs/SYSTEM_INTEGRITY.md)
- [TARX security policy](https://github.com/tarx-ai/tarx-desktop/blob/main/SECURITY.md)
- [Governed agent contracts](https://github.com/tarx-ai/governed-agent-contracts)
- [Attribute-based Commerce Checkout](https://patents.google.com/patent/US20150278931A1/en)
- [Multi-Device Session Identity](https://patents.google.com/patent/US20160119469/en)

## Work with me

I am interested in senior roles, advisory work, and focused engagements
involving:

- AI systems architecture and applied AI platforms
- Enterprise AI implementation and transformation
- Forward-deployed AI product work
- Agent governance, evaluation, and operational controls
- Enterprise search and knowledge systems
- AI product strategy, design, and conversational experiences

For roles, partnerships, or investment conversations:
[wantzjt@gmail.com](mailto:wantzjt@gmail.com).
