# AGENT.md

This repository provides a comprehensive production-ready system for intelligent automation and multi-agent orchestration within modern software development using Claude Code. It unifies specialized AI agents, multi-agent workflow orchestrators, agent skills, and development tools into a granular plugin architecture.

## Key Technologies & Frameworks
- **Claude Code**: The primary platform for plugin integration and execution.
- **Anthropic AI Models**: Utilizes Sonnet 4.5 and Haiku 4.5 for agent intelligence, with hybrid orchestration for optimal performance.
- **Python (FastAPI)**: Mentioned in examples for backend scaffolding.
- **Kubernetes, AWS/Azure/GCP**: Used for cloud infrastructure and operations.

## Main Features
- **Granular Plugin Architecture**: 63 focused, single-purpose plugins optimized for minimal token usage and composability.
- **Specialized Agents**: 85 domain-expert AI agents providing deep knowledge across various software development areas.
- **Agent Skills**: 47 modular knowledge packages with progressive disclosure, enhancing agent capabilities efficiently.
- **Workflow Orchestrators**: 15 multi-agent coordination systems for complex operations like full-stack development and security hardening.
- **Comprehensive Tooling**: 44 development tools for project scaffolding, security scanning, and test automation.

## Architectural Patterns
- **Granular Plugin Architecture**: Emphasizes single responsibility, minimal token usage, and composability through isolated plugins.
- **Progressive Disclosure (Skills)**: A three-tier architecture (Metadata, Instructions, Resources) for token efficiency, loading knowledge only when activated.
- **Hybrid Model Orchestration**: Strategic assignment of Haiku (fast execution) and Sonnet (complex reasoning) models, often in `Sonnet (planning) → Haiku (execution) → Sonnet (review)` patterns.