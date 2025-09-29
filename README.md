PromptLogicML

PromptLogicML is a semantic prompt engineering framework for large language models (LLMs), built on XML-like syntax enriched with MathML. It enables the modeling of regulatory timelines, conditional logic, and compliance structures across critical domains such as finance, AI governance, and modular dashboards.

Purpose

This project aims to transpose complex scenarios—such as financial reporting cycles or EU AI Act requirements—into structured, interpretable, and auditable prompts. Each event, condition, or threshold is encapsulated in a tagged grammar, readable by both humans and machines.

Repository Index

•	/prompts/ 
XML/MathML prompt templates organized by domain:
o	finance/ — IFRS, FINREP, variance thresholds
o	ai_regulation/ — EU AI Act, audits, risk classification

•	/schemas/
o	tags.xml — XML tag definitions
o	conditions.mathml — MathML logic blocks for compliance modeling

•	/examples/
o	Annotated walkthroughs and rendered outputs
o	Example timelines and decision logic

•	/docs/
o	Technical documentation
o	Semantic overlay guides and integration notes

•	/dashboards/
o	Mutation-tagged ledger models
o	Modular dashboard logic templates

•	/tests/
o	Schema validation scripts
o	Logic assertions and threshold checks

•	README.md 
Project overview and onboarding instructions

Features
- XML-tagged prompt scaffolding with embedded MathML logic
- Timeline modeling across multi-phase regulatory workflows
- Mutation-tagged logic for thresholds, escalation triggers, and audit checkpoints
- Modular semantic overlays for domain-specific enrichment

Advantages
- Supports financial and regulatory use cases (e.g., IFRS, FINREP, EU AI Act)
- Enables machine-readable logic for traceability, reproducibility, and auditability
- Integrates seamlessly into LLM pipelines and compliance dashboards

Benefits
- Reduces ambiguity in LLM outputs for regulated environments
- Facilitates interdisciplinary synthesis across legal, technical, and operational teams
- Accelerates deployment of interpretable, scalable prompt systems

Contributing
We welcome contributions from prompt engineers, regulatory architects, and semantic modelers.

To contribute:
1. Fork the repository
2. Create a branch (`feature/my-new-prompt`)
3. Add your files to the appropriate folder
4. Document your logic in `/docs`
5. Submit a pull request with description, rationale, and rendered example

See [CONTRIBUTING.md](CONTRIBUTING.md) for tag conventions, MathML standards, and review procedures.

Explore Further
- Browse prompt templates in `/prompts`
- Study logic structures in `/schemas`
- Follow walkthroughs in `/examples`
- Integrate structures into your own LLM pipelines

 License
This project is licensed under the [MIT License](LICENSE) — © 2025 Olivier RAZANAJATOVO.  
You are free to use, modify, and distribute this software with attribution.  
See the full license text in the `LICENSE` file.
